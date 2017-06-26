set(LUA_SRC
    lapi.c lcode.c ldebug.c ldo.c ldump.c lfunc.c lgc.c llex.c lmem.c
  	lobject.c lopcodes.c lparser.c lstate.c lstring.c ltable.c ltm.c
  	lundump.c lvm.c lzio.c strbuf.c fpconv.c
    lauxlib.c lbaselib.c ldblib.c liolib.c lmathlib.c loslib.c ltablib.c
  	lstrlib.c loadlib.c linit.c lua_cjson.c lua_struct.c lua_cmsgpack.c
  	lua_bit.c
)

add_library(lua STATIC
  ${LUA_SRC}
)
