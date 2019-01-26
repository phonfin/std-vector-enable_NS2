# std-vector-enable_NS2
Enable to use std::vector on ns-2.35

All the '.patch' file should be used on original ns-2.35.
COMMAND:
1. put '.patch' file outside ns-2.35 folder, but inside 'ns-allinone-2.35' folder.
2. type 'patch -p1 --ignore-whitespace -i vector_enable.patch'
3. the following changes of files will be list if previous operations are done properly
	patching file ns-2.35/mobile/god.cc
	patching file ns-2.35/mobile/god.h
	patching file ns-2.35/tcp/tcp-fack.cc
	patching file ns-2.35/tcp/tcp-fs.cc
	patching file ns-2.35/tcp/tcp-linux.cc
