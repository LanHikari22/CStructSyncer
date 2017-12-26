# CStructSyncer
This is a compilation of programs that can pad and sort C structs. 
They can also generate docs that can then be sync'd with their associated structs

# input
* A C structure typedef template. It is recompiled in a sense, and filled with the necessary pads so that it is functional.
* A document can also be generated and syncronized and merged with structs.

#Settings
* POINTER_SIZE in StructPadder.py may need to be modified as it is system dependent. It defaults to 32-bit
* int_types_long in StructPadder.py indicates whether unsigned/signed ints are displayed as uint32_t, or u32.
* known_types is a dictionary in StructPadder.py that specifies the sizes for all known types, including primitives and custom types.
