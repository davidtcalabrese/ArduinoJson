# ArduinoJson - https://arduinojson.org
# Copyright Benoit Blanchon 2014-2021
# MIT License

add_executable(TextFormatterTests 
	writeFloat.cpp
	writeString.cpp
)

set_target_properties(TextFormatterTests PROPERTIES UNITY_BUILD OFF)

add_test(TextFormatter TextFormatterTests)
