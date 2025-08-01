# Jacob's Mesh

This fork does two things for my Station G2 node:
1. Enables Store & Forward module on all channels. Default has a weird limitation. See https://github.com/jacobpretorius/mesh/commit/a17451582b3c4ffc877e75e0304119e12094e053
2. Sets the node as `is_unmessagable` without it having to be in ROUTER mode , see `src/modules/NodeInfoModule.cpp`

Use at your own risk. Seems to work fine for me.