
add_library(rapidjson INTERFACE)
add_library(rapidjson::rapidjson ALIAS rapidjson)
target_include_directories(rapidjson INTERFACE include/)
