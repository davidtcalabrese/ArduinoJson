# ArduinoJson - https://arduinojson.org
# Copyright Benoit Blanchon 2014-2021
# MIT License

add_executable(JsonDeserializerTests
	array.cpp
	array_static.cpp
	DeserializationError.cpp
	filter.cpp
	incomplete_input.cpp
	input_types.cpp
	invalid_input.cpp
	misc.cpp
	nestingLimit.cpp
	number.cpp
	object.cpp
	object_static.cpp
	string.cpp
)

set_target_properties(JsonDeserializerTests PROPERTIES UNITY_BUILD OFF)

add_test(JsonDeserializer JsonDeserializerTests)
