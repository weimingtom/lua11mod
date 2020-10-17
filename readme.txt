(1) lua_pushcfunction has two param: 
		public static void lua_register(CharPtr n, lua_CFunction f) { lua_pushcfunction(f, n.ToString()); lua_storeglobal(n); }


(2) breakpoint:
stringinput
