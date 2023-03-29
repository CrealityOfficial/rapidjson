__add_include_interface(rapidjson INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

if(CC_INSTALL_RAPIDJSON)
	__install_directory_specif(${CMAKE_CURRENT_SOURCE_DIR}/ rapidjson)
endif()