STM32 Work


To start a new project

# New project

-> Check CMSIS 	: CORE
-> Check Device : Startup

# Create simulated Target
-> Manage project item
	Change name to simulated
-> Option for Target
	Debug
	-> Check : Use simulator
	-> Check : Run to main

# Create real Target
-> Manage project item
	Add new target
-> Option for Target
	25MHZ
	check microlib if not needed
-> Debug
	Use ST-Link debug

Debug
-> Check : Run to main