package(
    default_testonly = 1,
    default_visibility = ["//visibility:private"],
)

licenses(["none"])

COPTS = [
    "-O3",
    "-Wall",
]

cc_library(
    name = "cppunit",
    srcs = [
	"src/cppunit/AdditionalMessage.cpp",
  	"src/cppunit/Asserter.cpp",
	"src/cppunit/BeOsDynamicLibraryManager.cpp",
  	"src/cppunit/BriefTestProgressListener.cpp",
	"src/cppunit/CompilerOutputter.cpp",
	"src/cppunit/DefaultProtector.cpp",
	"src/cppunit/DynamicLibraryManager.cpp",
	"src/cppunit/DynamicLibraryManagerException.cpp",
	"src/cppunit/Exception.cpp",
	"src/cppunit/Message.cpp",
	"src/cppunit/RepeatedTest.cpp",
	"src/cppunit/PlugInManager.cpp",
	"src/cppunit/PlugInParameters.cpp",
	"src/cppunit/Protector.cpp",
	"src/cppunit/ProtectorChain.cpp",
	"src/cppunit/SourceLine.cpp",
	"src/cppunit/StringTools.cpp",
	"src/cppunit/SynchronizedObject.cpp",
	"src/cppunit/Test.cpp",
	"src/cppunit/TestAssert.cpp",
	"src/cppunit/TestCase.cpp",
	"src/cppunit/TestCaseDecorator.cpp",
	"src/cppunit/TestComposite.cpp",
	"src/cppunit/TestDecorator.cpp",
	"src/cppunit/TestFactoryRegistry.cpp",
	"src/cppunit/TestFailure.cpp",
	"src/cppunit/TestLeaf.cpp",
	"src/cppunit/TestNamer.cpp",
	"src/cppunit/TestPath.cpp",
	"src/cppunit/TestPlugInDefaultImpl.cpp",
	"src/cppunit/TestResult.cpp",
	"src/cppunit/TestResultCollector.cpp",
	"src/cppunit/TestRunner.cpp",
	"src/cppunit/TestSetUp.cpp",
	"src/cppunit/TestSuccessListener.cpp",
	"src/cppunit/TestSuite.cpp",
	"src/cppunit/TestSuiteBuilderContext.cpp",
	"src/cppunit/TextOutputter.cpp",
	"src/cppunit/TextTestProgressListener.cpp",
	"src/cppunit/TextTestResult.cpp",
	"src/cppunit/TextTestRunner.cpp",
	"src/cppunit/TypeInfoHelper.cpp",
	"src/cppunit/UnixDynamicLibraryManager.cpp",
	"src/cppunit/ShlDynamicLibraryManager.cpp",
	"src/cppunit/XmlDocument.cpp",
	"src/cppunit/XmlElement.cpp",
	"src/cppunit/XmlOutputter.cpp",
	"src/cppunit/XmlOutputterHook.cpp",
	"src/cppunit/Win32DynamicLibraryManager.cpp",
    ],
    hdrs = glob([
        "src/cppunit/*.h",
	"config/*.h",
	"include/cppunit/*.h",
	"include/cppunit/**/*.h",
    ]),
    includes = [
	".",
        "include",
	"src/cppunit",
	"src/qttestrunner",
	"config",
    ],
    copts = COPTS,

    visibility = ["//visibility:public"],
)

