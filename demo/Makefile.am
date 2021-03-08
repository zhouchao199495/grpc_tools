AUTOMAKE_OPTIONS=foreign
bin_PROGRAMS=test test2

test_SOURCES=msg.pb.h msg.pb.cc main.cpp
test2_SOURCES=msg.pb.h msg.pb.cc test.cpp

test_CPPFLAGS=-I../include -L../lib -std=gnu++11 `pkg-config --cflags --libs protobuf`
test2_CPPFLAGS=-I../include -L../lib -std=gnu++11 `pkg-config --cflags --libs protobuf`

test_LDADD=-lpthread -lprotobuf
test2_LDADD=-lpthread -lprotobuf
