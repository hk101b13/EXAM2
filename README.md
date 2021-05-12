# EXAM2

# main()
mbed run the RPC loop to get input string commands from PC/Python, and it will in turn call custom RPC functions.

# rpc_function.py
PC/Python use RPC over serial to send a command to call accelerator capture mode on mbed

# ac_capture_mode()
In this accelerator capture mode, mbed will start a thread function

# machine_learning()
In this accelerator capture function, mbed will record a set of accelerator data values (as in mbed lab 8).

#  WIFI_Function()、publish_message()
publish the classified gesture as an event (gesture ID and sequence number of the event) through WiFi/MQTT to a broker.
