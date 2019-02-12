# Modified wordpress docker image

This is a tiny patch for the official WordPress docker image which
prevents saving the database password in the config file. Instead
WordPress always takes it from the environment directly.
