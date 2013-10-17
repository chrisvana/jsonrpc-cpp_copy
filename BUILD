// json c++ rpc
[
{ "config" : {
   "component": "jsonrpc-cpp"
} },
{ "cc_library": {
    "name": "jsonrpc",
    "cc_headers": [ "*.h" ],
    "cc_sources": [ "src/*.cpp" ],
    "cc_linker_args": [ "-lcurl" ],
    "dependencies": [ "//third_party/json:json" ]
} },
{ "cc_library": {
    "name": "jsonrpc_installed",
    "dependencies": [ ":jsonrpc" ],
    "cc_include_dirs": [ "." ]
} }
] 