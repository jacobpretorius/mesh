# Jacob's Mesh

This fork does two things for my Station G2 node:
1. Enables Store & Forward module on all channels. Default has a weird limitation. See https://github.com/jacobpretorius/mesh/commit/a17451582b3c4ffc877e75e0304119e12094e053#diff-1d80220dd52a32b7e52b959663faa3808c5f38a5f0dd3b09ee1fba55072dddfe
2. Sets the node as `is_unmessagable` without it having to be in ROUTER mode. This doesn't actually make it unmessageable, it only adds the "unmonitored" status in the app UI for this node so others know not to DM it and expect a reply. See https://github.com/jacobpretorius/mesh/commit/e92811081b8ddfa2185d9e7681717e3c2f6336a9#diff-01f914af6c343116ef1c2cc30d6de647a3ec5cdbc86a7debdf02cd6f29f7c18b

Use at your own risk. Seems to work fine for me.
