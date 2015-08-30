# XcodeBuilder

预想功能
1. 支持添加/删除文件
2. 支持添加/删除framework
3. 支持添加/删除Shell
4. 支持编辑BuildSting

功能实现
第一步分析.pbxpro
.pbxproj结构
PBXObject
	PBXBuildFile
	PBXBuildPhase
		PBXFrameworksBuildPhase
		PBXResourcesBuildPhase
		PBXShellScriptBuildPhase
		PBXSourcesBuildPhase
	PBXProject
	PBXGroup
	PBXNativeTarget
	PBXVariantGroup
XCProjectFile
	XCBuildConfiguration
	XCConfigurationList
