cc_binary(
  name = "wsdl2cpp",
  srcs = [
    "main.cpp",
    "main.h",
    "wsdl.cpp",
    "wsdl.h",
    "wsdlmessage.h",
    "wsdlmessage.cpp",
    "wsdlmessagepart.cpp",
    "wsdlmessagepart.h",
    "wsdlporttype.cpp",
    "wsdlporttype.h",
    "wsdloperation.cpp",
    "wsdloperation.h",
    "xsd.cpp",
    "xsd.h",
    "xsdelement.cpp",
    "xsdelement.h",
    "xsdsimpletype.cpp",
    "xsdsimpletype.h",
    "xsdcomplextype.cpp",
    "xsdcomplextype.h",
    "path.cpp",
    "path.h",
    "typegenerator.cpp",
    "typegenerator.h",
  ],
  copts = [
    "-I/usr/include/libxml2",
  ],
  linkopts = [
    "-lxml2",
    "-ldl",
    "-lpthread",
    "-lcurl",
  ],
)