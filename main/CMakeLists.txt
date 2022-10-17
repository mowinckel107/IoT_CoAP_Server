


idf_component_register(
	SRCS # list the source files of this component
	"coap_server_example_main.c"
	"LocalLibraries/dht11.c"
	
	INCLUDE_DIRS
	"."
	"LocalLibraries"

	EMBED_TXTFILES certs/coap_ca.pem certs/coap_server.crt certs/coap_server.key)
