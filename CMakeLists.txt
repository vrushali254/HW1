project( facial_features )
find_package( OpenCV REQUIRED )
add_executable( facial_features facial_features.cpp )
target_link_libraries( facial_features ${OpenCV_LIBS} )