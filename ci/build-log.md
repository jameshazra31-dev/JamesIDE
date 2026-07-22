# Build log (last 500 lines)

~~~
> Task :termux:emulator:processDebugJavaRes NO-SOURCE
> Task :logging:logsender:processDebugJavaRes NO-SOURCE
> Task :termux:view:processDebugJavaRes NO-SOURCE
> Task :utilities:preferences:processDebugJavaRes
> Task :utilities:treeview:processDebugJavaRes NO-SOURCE
> Task :utilities:flashbar:processDebugJavaRes
> Task :external:acsprovider:bundleLibRuntimeToJarDebug
> Task :core:common:bundleLibRuntimeToJarDebug
> Task :core:resources:bundleLibRuntimeToJarDebug
> Task :event:eventbus-android:bundleLibRuntimeToJarDebug
> Task :event:eventbus-events:bundleLibRuntimeToJarDebug
> Task :core:app:desugarDebugFileDependencies SKIPPED
> Task :utilities:flashbar:bundleLibRuntimeToJarDebug
> Task :core:app:checkDebugDuplicateClasses

> Task :termux:shared:compileDebugJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.

> Task :xml:resources-api:compileDebugKotlin
w: file:///home/runner/work/JamesIDE/JamesIDE/xml/resources-api/src/main/java/com/android/aaptcompiler/StringPool.kt:363:39 'fun toShort(): Short' is deprecated. Conversion of Char to Number is deprecated. Use Char.code property instead.
w: file:///home/runner/work/JamesIDE/JamesIDE/xml/resources-api/src/main/java/com/android/aaptcompiler/buffer/BigBuffer.kt:44:23 Non-public primary constructor is exposed via the generated 'copy()' method of the 'data' class.

The generated 'copy()' will change its visibility in future releases.

To suppress the warning do one of the following:
- Annotate the data class with the '@ConsistentCopyVisibility' annotation.
- Use the '-Xconsistent-data-class-copy-visibility' compiler flag.
- Annotate the data class with the '@ExposedCopyVisibility' annotation 
  (Discouraged, but can be used to keep binary compatibility).

To learn more, see the documentation of the '@ConsistentCopyVisibility' and '@ExposedCopyVisibility' annotations.

This will become an error in Kotlin 2.2.

> Task :xml:resources-api:compileDebugJavaWithJavac
/home/runner/work/JamesIDE/JamesIDE/xml/resources-api/src/main/proto_java/com/android/aapt/Resources.java:19158: warning: [dep-ann] deprecated item is not annotated with @Deprecated
    private void setDimensionValueDeprecated(float value) {
                 ^
/home/runner/work/JamesIDE/JamesIDE/xml/resources-api/src/main/proto_java/com/android/aapt/Resources.java:19167: warning: [dep-ann] deprecated item is not annotated with @Deprecated
    private void clearDimensionValueDeprecated() {
                 ^
/home/runner/work/JamesIDE/JamesIDE/xml/resources-api/src/main/proto_java/com/android/aapt/Resources.java:19204: warning: [dep-ann] deprecated item is not annotated with @Deprecated
    private void setFractionValueDeprecated(float value) {
                 ^
/home/runner/work/JamesIDE/JamesIDE/xml/resources-api/src/main/proto_java/com/android/aapt/Resources.java:19213: warning: [dep-ann] deprecated item is not annotated with @Deprecated
    private void clearFractionValueDeprecated() {
                 ^
4 warnings

> Task :external:atc:bundleLibRuntimeToJarDebug
> Task :xml:resources-api:bundleLibCompileToJarDebug
> Task :external:logwire:bundleLibRuntimeToJarDebug
> Task :xml:resources-api:processDebugJavaRes
> Task :core:actions:bundleLibRuntimeToJarDebug
> Task :core:lsp-models:bundleLibRuntimeToJarDebug
> Task :core:app:mergeExtDexDebug
> Task :xml:aaptcompiler:compileDebugKotlin
> Task :termux:shared:bundleLibCompileToJarDebug
> Task :termux:shared:mergeDebugShaders
> Task :termux:shared:compileDebugShaders NO-SOURCE
> Task :termux:shared:generateDebugAssets UP-TO-DATE
> Task :core:projectdata:bundleLibRuntimeToJarDebug
> Task :termux:shared:mergeDebugAssets
> Task :termux:shared:processDebugJavaRes NO-SOURCE
> Task :utilities:preferences:bundleLibRuntimeToJarDebug
> Task :java:javac-services:bundleLibRuntimeToJarDebug
> Task :ideconfigurations:bundleLibRuntimeToJarDebug
> Task :xml:resources-api:bundleLibRuntimeToJarDebug
> Task :termux:emulator:bundleLibRuntimeToJarDebug
> Task :termux:shared:bundleLibRuntimeToJarDebug
> Task :termux:view:bundleLibRuntimeToJarDebug
> Task :logging:idestats:bundleLibRuntimeToJarDebug
> Task :utilities:treeview:bundleLibRuntimeToJarDebug
> Task :logging:logsender:bundleLibRuntimeToJarDebug

> Task :xml:aaptcompiler:compileDebugKotlin
w: file:///home/runner/work/JamesIDE/JamesIDE/xml/aaptcompiler/src/main/java/com/android/aaptcompiler/proto/ProtoDeserialize.kt:421:33 'fun getDimensionValueDeprecated(): Float' is deprecated. Deprecated in Java.
w: file:///home/runner/work/JamesIDE/JamesIDE/xml/aaptcompiler/src/main/java/com/android/aaptcompiler/proto/ProtoDeserialize.kt:426:33 'fun getFractionValueDeprecated(): Float' is deprecated. Deprecated in Java.

> Task :xml:aaptcompiler:compileDebugJavaWithJavac
> Task :xml:aaptcompiler:bundleLibCompileToJarDebug
> Task :xml:aaptcompiler:processDebugJavaRes
> Task :xml:aaptcompiler:bundleLibRuntimeToJarDebug
> Task :ideconfigurations:mergeDebugJniLibFolders
> Task :ideconfigurations:mergeDebugNativeLibs NO-SOURCE
> Task :ideconfigurations:copyDebugJniLibsProjectOnly
> Task :core:actions:mergeDebugJniLibFolders
> Task :core:actions:mergeDebugNativeLibs NO-SOURCE
> Task :core:actions:copyDebugJniLibsProjectOnly
> Task :core:common:mergeDebugJniLibFolders
> Task :core:common:mergeDebugNativeLibs NO-SOURCE
> Task :core:common:copyDebugJniLibsProjectOnly
> Task :core:indexing-api:mergeDebugJniLibFolders
> Task :core:indexing-api:mergeDebugNativeLibs NO-SOURCE
> Task :core:indexing-api:copyDebugJniLibsProjectOnly
> Task :core:indexing-core:mergeDebugJniLibFolders
> Task :core:indexing-core:mergeDebugNativeLibs NO-SOURCE
> Task :core:indexing-core:copyDebugJniLibsProjectOnly
> Task :core:lsp-api:mergeDebugJniLibFolders
> Task :core:lsp-api:mergeDebugNativeLibs NO-SOURCE
> Task :core:lsp-api:copyDebugJniLibsProjectOnly
> Task :core:lsp-models:mergeDebugJniLibFolders
> Task :core:lsp-models:mergeDebugNativeLibs NO-SOURCE
> Task :core:lsp-models:copyDebugJniLibsProjectOnly
> Task :core:projectdata:mergeDebugJniLibFolders
> Task :core:projectdata:mergeDebugNativeLibs NO-SOURCE
> Task :core:projectdata:copyDebugJniLibsProjectOnly
> Task :core:projects:mergeDebugJniLibFolders
> Task :core:projects:mergeDebugNativeLibs NO-SOURCE
> Task :core:projects:copyDebugJniLibsProjectOnly
> Task :core:resources:mergeDebugJniLibFolders
> Task :core:resources:mergeDebugNativeLibs NO-SOURCE
> Task :core:resources:copyDebugJniLibsProjectOnly
> Task :editor:api:mergeDebugJniLibFolders
> Task :editor:api:mergeDebugNativeLibs NO-SOURCE
> Task :editor:api:copyDebugJniLibsProjectOnly
> Task :editor:impl:mergeDebugJniLibFolders
> Task :editor:impl:mergeDebugNativeLibs NO-SOURCE
> Task :editor:impl:copyDebugJniLibsProjectOnly
> Task :editor:treesitter:mergeDebugJniLibFolders
> Task :editor:treesitter:mergeDebugNativeLibs NO-SOURCE
> Task :editor:treesitter:copyDebugJniLibsProjectOnly
> Task :event:eventbus-android:mergeDebugJniLibFolders
> Task :event:eventbus-android:mergeDebugNativeLibs NO-SOURCE
> Task :event:eventbus-android:copyDebugJniLibsProjectOnly
> Task :event:eventbus-events:mergeDebugJniLibFolders
> Task :event:eventbus-events:mergeDebugNativeLibs NO-SOURCE
> Task :event:eventbus-events:copyDebugJniLibsProjectOnly
> Task :external:acsprovider:mergeDebugJniLibFolders
> Task :external:acsprovider:mergeDebugNativeLibs NO-SOURCE
> Task :external:acsprovider:copyDebugJniLibsProjectOnly
> Task :external:atc:mergeDebugJniLibFolders
> Task :external:atc:mergeDebugNativeLibs NO-SOURCE
> Task :external:atc:copyDebugJniLibsProjectOnly
> Task :external:logwire:mergeDebugJniLibFolders
> Task :external:logwire:mergeDebugNativeLibs NO-SOURCE
> Task :external:logwire:copyDebugJniLibsProjectOnly
> Task :java:javac-services:mergeDebugJniLibFolders
> Task :java:javac-services:mergeDebugNativeLibs NO-SOURCE
> Task :java:javac-services:copyDebugJniLibsProjectOnly
> Task :java:lsp:mergeDebugJniLibFolders
> Task :java:lsp:mergeDebugNativeLibs NO-SOURCE
> Task :java:lsp:copyDebugJniLibsProjectOnly
> Task :java:lsp-setup:mergeDebugJniLibFolders
> Task :java:lsp-setup:mergeDebugNativeLibs NO-SOURCE
> Task :java:lsp-setup:copyDebugJniLibsProjectOnly
> Task :logging:idestats:mergeDebugJniLibFolders
> Task :logging:logsender:mergeDebugJniLibFolders
> Task :logging:idestats:mergeDebugNativeLibs NO-SOURCE
> Task :logging:logsender:mergeDebugNativeLibs NO-SOURCE
> Task :logging:idestats:copyDebugJniLibsProjectOnly
> Task :logging:logsender:copyDebugJniLibsProjectOnly
> Task :termux:application:mergeDebugJniLibFolders
> Task :termux:emulator:configureNdkBuildDebug[arm64-v8a]
> Task :termux:application:mergeDebugNativeLibs
> Task :termux:emulator:buildNdkBuildDebug[arm64-v8a]
> Task :termux:application:copyDebugJniLibsProjectOnly
> Task :termux:emulator:configureNdkBuildDebug[armeabi-v7a]
> Task :termux:shared:configureNdkBuildDebug[arm64-v8a]
> Task :termux:emulator:buildNdkBuildDebug[armeabi-v7a]
> Task :termux:emulator:mergeDebugJniLibFolders
> Task :termux:emulator:mergeDebugNativeLibs
> Task :termux:emulator:copyDebugJniLibsProjectOnly
> Task :termux:view:mergeDebugJniLibFolders
> Task :termux:view:mergeDebugNativeLibs NO-SOURCE
> Task :termux:view:copyDebugJniLibsProjectOnly
> Task :utilities:flashbar:mergeDebugJniLibFolders
> Task :utilities:flashbar:mergeDebugNativeLibs NO-SOURCE
> Task :utilities:flashbar:copyDebugJniLibsProjectOnly
> Task :utilities:preferences:mergeDebugJniLibFolders
> Task :utilities:preferences:mergeDebugNativeLibs NO-SOURCE
> Task :utilities:preferences:copyDebugJniLibsProjectOnly
> Task :utilities:templates-api:mergeDebugJniLibFolders
> Task :utilities:templates-api:mergeDebugNativeLibs NO-SOURCE
> Task :utilities:templates-api:copyDebugJniLibsProjectOnly
> Task :utilities:templates-impl:mergeDebugJniLibFolders
> Task :utilities:templates-impl:mergeDebugNativeLibs NO-SOURCE
> Task :utilities:templates-impl:copyDebugJniLibsProjectOnly
> Task :utilities:treeview:mergeDebugJniLibFolders
> Task :utilities:treeview:mergeDebugNativeLibs NO-SOURCE
> Task :utilities:treeview:copyDebugJniLibsProjectOnly
> Task :utilities:uidesigner:mergeDebugJniLibFolders
> Task :utilities:uidesigner:mergeDebugNativeLibs NO-SOURCE
> Task :utilities:uidesigner:copyDebugJniLibsProjectOnly
> Task :utilities:xml-inflater:mergeDebugJniLibFolders
> Task :utilities:xml-inflater:mergeDebugNativeLibs NO-SOURCE
> Task :utilities:xml-inflater:copyDebugJniLibsProjectOnly
> Task :xml:aaptcompiler:mergeDebugJniLibFolders
> Task :xml:aaptcompiler:mergeDebugNativeLibs NO-SOURCE
> Task :xml:aaptcompiler:copyDebugJniLibsProjectOnly
> Task :xml:lsp:mergeDebugJniLibFolders
> Task :xml:lsp:mergeDebugNativeLibs NO-SOURCE
> Task :xml:lsp:copyDebugJniLibsProjectOnly
> Task :xml:resources-api:mergeDebugJniLibFolders
> Task :xml:resources-api:mergeDebugNativeLibs NO-SOURCE
> Task :xml:resources-api:copyDebugJniLibsProjectOnly
> Task :xml:utils:mergeDebugJniLibFolders
> Task :xml:utils:mergeDebugNativeLibs NO-SOURCE
> Task :xml:utils:copyDebugJniLibsProjectOnly

> Task :xml:utils:kaptGenerateStubsDebugKotlin
w: Support for language version 2.0+ in kapt is in Alpha and must be enabled explicitly. Falling back to 1.9.

> Task :termux:shared:buildNdkBuildDebug[arm64-v8a]
> Task :termux:shared:configureNdkBuildDebug[armeabi-v7a]
> Task :termux:shared:buildNdkBuildDebug[armeabi-v7a]
> Task :termux:shared:mergeDebugJniLibFolders
> Task :xml:utils:kaptDebugKotlin
> Task :termux:shared:mergeDebugNativeLibs
> Task :termux:shared:copyDebugJniLibsProjectOnly
> Task :xml:utils:compileDebugKotlin
> Task :xml:utils:compileDebugJavaWithJavac
> Task :xml:utils:bundleLibCompileToJarDebug
> Task :xml:utils:processDebugJavaRes
> Task :xml:utils:bundleLibRuntimeToJarDebug

> Task :core:projects:kaptGenerateStubsDebugKotlin
w: Support for language version 2.0+ in kapt is in Alpha and must be enabled explicitly. Falling back to 1.9.

> Task :utilities:templates-api:compileDebugKotlin
> Task :utilities:templates-api:compileDebugJavaWithJavac
> Task :utilities:templates-api:processDebugJavaRes
> Task :utilities:templates-api:bundleLibCompileToJarDebug
> Task :utilities:templates-api:bundleLibRuntimeToJarDebug
> Task :core:projects:kaptDebugKotlin

> Task :core:projects:compileDebugKotlin
w: file:///home/runner/work/JamesIDE/JamesIDE/core/projects/src/main/java/com/tom/rv2ide/projects/classpath/ClassInfo.kt:27:1 Non-public primary constructor is exposed via the generated 'copy()' method of the 'data' class.

The generated 'copy()' will change its visibility in future releases.

To suppress the warning do one of the following:
- Annotate the data class with the '@ConsistentCopyVisibility' annotation.
- Use the '-Xconsistent-data-class-copy-visibility' compiler flag.
- Annotate the data class with the '@ExposedCopyVisibility' annotation 
  (Discouraged, but can be used to keep binary compatibility).

To learn more, see the documentation of the '@ConsistentCopyVisibility' and '@ExposedCopyVisibility' annotations.

This will become an error in Kotlin 2.2.

> Task :core:projects:compileDebugJavaWithJavac
> Task :core:projects:bundleLibCompileToJarDebug
> Task :core:projects:processDebugJavaRes

> Task :core:indexing-api:kaptGenerateStubsDebugKotlin
w: Support for language version 2.0+ in kapt is in Alpha and must be enabled explicitly. Falling back to 1.9.

> Task :core:lsp-api:kaptGenerateStubsDebugKotlin
w: Support for language version 2.0+ in kapt is in Alpha and must be enabled explicitly. Falling back to 1.9.

> Task :core:indexing-api:kaptDebugKotlin
> Task :core:lsp-api:kaptDebugKotlin
> Task :core:indexing-api:compileDebugKotlin
> Task :termux:application:compileDebugKotlin
> Task :core:indexing-api:compileDebugJavaWithJavac
> Task :core:indexing-api:bundleLibCompileToJarDebug
> Task :core:lsp-api:compileDebugKotlin

> Task :core:indexing-core:kaptGenerateStubsDebugKotlin
w: Support for language version 2.0+ in kapt is in Alpha and must be enabled explicitly. Falling back to 1.9.

> Task :core:lsp-api:compileDebugJavaWithJavac
> Task :core:lsp-api:bundleLibCompileToJarDebug

> Task :termux:application:compileDebugJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.

> Task :core:indexing-core:kaptDebugKotlin
> Task :core:indexing-core:compileDebugKotlin
> Task :core:indexing-core:compileDebugJavaWithJavac
> Task :core:indexing-core:bundleLibCompileToJarDebug
> Task :termux:application:bundleLibCompileToJarDebug
> Task :editor:api:compileDebugKotlin
> Task :editor:api:compileDebugJavaWithJavac
> Task :editor:api:bundleLibCompileToJarDebug

> Task :xml:lsp:kaptGenerateStubsDebugKotlin
w: Support for language version 2.0+ in kapt is in Alpha and must be enabled explicitly. Falling back to 1.9.

> Task :utilities:templates-impl:kaptGenerateStubsDebugKotlin
w: Support for language version 2.0+ in kapt is in Alpha and must be enabled explicitly. Falling back to 1.9.

> Task :editor:treesitter:compileDebugKotlin
w: file:///home/runner/work/JamesIDE/JamesIDE/editor/treesitter/src/main/java/io/github/rosemoe/sora/editor/ts/TsAnalyzeWorker.kt:68:46 This declaration needs opt-in. Its usage should be marked with '@kotlinx.coroutines.ExperimentalCoroutinesApi' or '@OptIn(kotlinx.coroutines.ExperimentalCoroutinesApi::class)'
w: file:///home/runner/work/JamesIDE/JamesIDE/editor/treesitter/src/main/java/io/github/rosemoe/sora/editor/ts/TsAnalyzeWorker.kt:108:5 This declaration needs opt-in. Its usage should be marked with '@kotlinx.coroutines.ExperimentalCoroutinesApi' or '@OptIn(kotlinx.coroutines.ExperimentalCoroutinesApi::class)'

> Task :editor:treesitter:compileDebugJavaWithJavac
> Task :editor:treesitter:bundleLibCompileToJarDebug
> Task :utilities:templates-impl:kaptDebugKotlin
> Task :xml:lsp:kaptDebugKotlin
> Task :utilities:templates-impl:compileDebugKotlin
> Task :xml:lsp:compileDebugKotlin
> Task :utilities:templates-impl:compileDebugJavaWithJavac
> Task :utilities:templates-impl:bundleLibCompileToJarDebug
> Task :xml:lsp:compileDebugJavaWithJavac
> Task :xml:lsp:bundleLibCompileToJarDebug
> Task :core:indexing-api:processDebugJavaRes
> Task :core:indexing-core:processDebugJavaRes
> Task :core:lsp-api:processDebugJavaRes
> Task :editor:api:processDebugJavaRes
> Task :editor:treesitter:processDebugJavaRes
> Task :termux:application:processDebugJavaRes
> Task :utilities:templates-impl:processDebugJavaRes
> Task :xml:lsp:processDebugJavaRes
> Task :core:indexing-api:bundleLibRuntimeToJarDebug
> Task :core:lsp-api:bundleLibRuntimeToJarDebug
> Task :core:projects:bundleLibRuntimeToJarDebug
> Task :editor:api:bundleLibRuntimeToJarDebug
> Task :editor:treesitter:bundleLibRuntimeToJarDebug
> Task :xml:lsp:bundleLibRuntimeToJarDebug
> Task :core:indexing-core:bundleLibRuntimeToJarDebug
> Task :termux:application:bundleLibRuntimeToJarDebug
> Task :utilities:templates-impl:bundleLibRuntimeToJarDebug
> Task :utilities:xml-inflater:kspDebugKotlin

> Task :java:lsp:kaptGenerateStubsDebugKotlin
w: Support for language version 2.0+ in kapt is in Alpha and must be enabled explicitly. Falling back to 1.9.

> Task :utilities:xml-inflater:compileDebugKotlin
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/xml-inflater/src/main/java/com/tom/rv2ide/inflater/internal/adapters/BaseButtonAdapter.kt:97:28 Unchecked cast of 'android.view.View' to 'T'.
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/xml-inflater/src/main/java/com/tom/rv2ide/inflater/internal/utils/ViewFactory.kt:76:17 Java type mismatch: inferred type is 'java.lang.Class<in CapturedType(in android.view.ViewGroup)!>?', but 'java.lang.Class<in android.view.ViewGroup>' was expected.

> Task :java:lsp:kaptDebugKotlin

> Task :utilities:xml-inflater:compileDebugJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.

> Task :utilities:xml-inflater:processDebugJavaRes
> Task :utilities:xml-inflater:bundleLibCompileToJarDebug
> Task :utilities:xml-inflater:bundleLibRuntimeToJarDebug

> Task :java:lsp:compileDebugKotlin
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/clang/ClangCompletionConverter.kt:62:30 Condition is always 'true'.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/clang/ClangLanguageServer.kt:191:11 Condition is always 'true'.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/java/utils/JavaParserUtils.kt:595:45 'val first: Optional<ClassOrInterfaceType!>!' is deprecated. This declaration will be renamed in a future version of Kotlin. Please consider using the 'first()' stdlib extension if the collection supports fast random access.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/java/utils/JavaParserUtils.kt:595:45 This synthetic property is based on the getter function 'fun getFirst(): Optional<ClassOrInterfaceType!>!' from Kotlin. In the future, synthetic properties will be available only if the base getter function came from Java. Consider replacing this property access with a 'getFirst()' function call.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/java/utils/JavaParserUtils.kt:608:45 'val first: Optional<ClassOrInterfaceType!>!' is deprecated. This declaration will be renamed in a future version of Kotlin. Please consider using the 'first()' stdlib extension if the collection supports fast random access.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/java/utils/JavaParserUtils.kt:608:45 This synthetic property is based on the getter function 'fun getFirst(): Optional<ClassOrInterfaceType!>!' from Kotlin. In the future, synthetic properties will be available only if the base getter function came from Java. Consider replacing this property access with a 'getFirst()' function call.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/java/utils/JavaParserUtils.kt:623:37 'val first: Optional<Type!>!' is deprecated. This declaration will be renamed in a future version of Kotlin. Please consider using the 'first()' stdlib extension if the collection supports fast random access.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/java/utils/JavaParserUtils.kt:623:37 This synthetic property is based on the getter function 'fun getFirst(): Optional<Type!>!' from Kotlin. In the future, synthetic properties will be available only if the base getter function came from Java. Consider replacing this property access with a 'getFirst()' function call.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/java/utils/JavaParserUtils.kt:633:28 'val first: Optional<ClassOrInterfaceType!>!' is deprecated. This declaration will be renamed in a future version of Kotlin. Please consider using the 'first()' stdlib extension if the collection supports fast random access.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/java/utils/JavaParserUtils.kt:633:28 This synthetic property is based on the getter function 'fun getFirst(): Optional<ClassOrInterfaceType!>!' from Kotlin. In the future, synthetic properties will be available only if the base getter function came from Java. Consider replacing this property access with a 'getFirst()' function call.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/kotlin/KotlinDiagnosticRenderer.kt:40:11 Condition is always 'false'.
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp/src/main/java/com/tom/rv2ide/lsp/kotlin/KotlinLanguageServer.kt:314:11 Condition is always 'true'.

> Task :java:lsp:compileDebugJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.

> Task :java:lsp:processDebugJavaRes
> Task :java:lsp:bundleLibCompileToJarDebug
> Task :java:lsp:bundleLibRuntimeToJarDebug
> Task :editor:impl:kspDebugKotlin

> Task :editor:impl:kaptGenerateStubsDebugKotlin
w: Support for language version 2.0+ in kapt is in Alpha and must be enabled explicitly. Falling back to 1.9.

> Task :editor:impl:kaptDebugKotlin

> Task :editor:impl:compileDebugKotlin
w: file:///home/runner/work/JamesIDE/JamesIDE/editor/impl/src/main/java/com/tom/rv2ide/editor/ui/CompletionTooltipManager.kt:157:37 'val defaultDisplay: Display!' is deprecated. Deprecated in Java.
w: file:///home/runner/work/JamesIDE/JamesIDE/editor/impl/src/main/java/com/tom/rv2ide/editor/ui/CompletionTooltipManager.kt:157:52 'val width: Int' is deprecated. Deprecated in Java.
w: file:///home/runner/work/JamesIDE/JamesIDE/editor/impl/src/main/java/io/github/rosemoe/sora/widget/IDEEditorSearcher.kt:52:16 This declaration overrides a deprecated member but is not marked as deprecated itself. Please add the '@Deprecated' annotation or suppress the diagnostic.
w: file:///home/runner/work/JamesIDE/JamesIDE/editor/impl/src/main/java/io/github/rosemoe/sora/widget/IDEEditorSearcher.kt:54:11 'fun replaceThis(p0: String): Unit' is deprecated. Deprecated in Java.

> Task :editor:impl:compileDebugJavaWithJavac
> Task :editor:impl:bundleLibCompileToJarDebug
> Task :editor:impl:processDebugJavaRes
> Task :editor:impl:bundleLibRuntimeToJarDebug

> Task :java:lsp-setup:compileDebugKotlin
w: file:///home/runner/work/JamesIDE/JamesIDE/java/lsp-setup/src/main/java/com/tom/rv2ide/setup/Setup.kt:250:74 'fun String.capitalize(): String' is deprecated. Use replaceFirstChar instead.

> Task :java:lsp-setup:compileDebugJavaWithJavac
> Task :java:lsp-setup:processDebugJavaRes
> Task :java:lsp-setup:bundleLibCompileToJarDebug
> Task :java:lsp-setup:bundleLibRuntimeToJarDebug

> Task :utilities:uidesigner:compileDebugKotlin
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/uidesigner/src/main/java/com/tom/rv2ide/uidesigner/utils/BackgroundPreviewExtensions.kt:628:13 Condition is always 'false'.
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/uidesigner/src/main/java/com/tom/rv2ide/uidesigner/utils/MaterialButtonRenderer.kt:608:68 'field scaledDensity: Float' is deprecated. Deprecated in Java.
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/uidesigner/src/main/java/com/tom/rv2ide/uidesigner/utils/VectorDrawableRenderer.kt:130:11 Condition is always 'true'.
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/uidesigner/src/main/java/com/tom/rv2ide/uidesigner/utils/views/AppBarLayoutM3Extensions.kt:66:7 'var targetElevation: Float' is deprecated. Deprecated in Java.
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/uidesigner/src/main/java/com/tom/rv2ide/uidesigner/utils/views/BadgeDrawableM3Extensions.kt:131:41 'static field BOTTOM_END: Int' is deprecated. Deprecated in Java.
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/uidesigner/src/main/java/com/tom/rv2ide/uidesigner/utils/views/BadgeDrawableM3Extensions.kt:132:43 'static field BOTTOM_START: Int' is deprecated. Deprecated in Java.
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/uidesigner/src/main/java/com/tom/rv2ide/uidesigner/utils/views/MaterialButtonM3Extensions.kt:179:68 'field scaledDensity: Float' is deprecated. Deprecated in Java.
w: file:///home/runner/work/JamesIDE/JamesIDE/utilities/uidesigner/src/main/java/com/tom/rv2ide/uidesigner/utils/views/TextInputEditTextM3Extensions.kt:136:68 'field scaledDensity: Float' is deprecated. Deprecated in Java.

> Task :utilities:uidesigner:compileDebugJavaWithJavac
> Task :utilities:uidesigner:processDebugJavaRes
> Task :utilities:uidesigner:bundleLibCompileToJarDebug
> Task :utilities:uidesigner:bundleLibRuntimeToJarDebug
> Task :core:app:mergeExtDexDebug FAILED
gradle/actions: Writing build results to /home/runner/work/_temp/.gradle-actions/build-results/__run_2-1784696509242.json

[Incubating] Problems report is available at: file:///home/runner/work/JamesIDE/JamesIDE/build/reports/problems/problems-report.html

FAILURE: Build failed with an exception.

* What went wrong:
A problem was found with the configuration of task ':core:app:mergeExtDexDebug' (type 'DexMergingTask').
  - In plugin 'com.android.internal.version-check' type 'com.android.build.gradle.internal.tasks.DexMergingTask' property 'fileDependencyDexDir' specifies directory '/home/runner/work/JamesIDE/JamesIDE/core/app/build/intermediates/external_file_lib_dex_archives/debug/desugarDebugFileDependencies' which doesn't exist.
    
    Reason: An input file was expected to be present but it doesn't exist.
    
    Possible solutions:
      1. Make sure the directory exists before the task is called.
      2. Make sure that the task which produces the directory is declared as an input.
    
    For more information, please refer to https://docs.gradle.org/8.13/userguide/validation_problems.html#input_file_does_not_exist in the Gradle documentation.

* Try:
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.
> Get more help at https://help.gradle.org.

* Exception is:
org.gradle.internal.execution.WorkValidationException: A problem was found with the configuration of task ':core:app:mergeExtDexDebug' (type 'DexMergingTask').
  - In plugin 'com.android.internal.version-check' type 'com.android.build.gradle.internal.tasks.DexMergingTask' property 'fileDependencyDexDir' specifies directory '/home/runner/work/JamesIDE/JamesIDE/core/app/build/intermediates/external_file_lib_dex_archives/debug/desugarDebugFileDependencies' which doesn't exist.
    
    Reason: An input file was expected to be present but it doesn't exist.
    
    Possible solutions:
      1. Make sure the directory exists before the task is called.
      2. Make sure that the task which produces the directory is declared as an input.
    
    For more information, please refer to https://docs.gradle.org/8.13/userguide/validation_problems.html#input_file_does_not_exist in the Gradle documentation.
	at org.gradle.internal.execution.WorkValidationException$BuilderWithSummary.build(WorkValidationException.java:137)
	at org.gradle.internal.execution.WorkValidationException$BuilderWithSummary.get(WorkValidationException.java:119)
	at org.gradle.internal.execution.steps.ValidateStep.throwValidationException(ValidateStep.java:174)
	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:99)
	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:56)
	at org.gradle.internal.execution.steps.AbstractCaptureStateBeforeExecutionStep.execute(AbstractCaptureStateBeforeExecutionStep.java:64)
	at org.gradle.internal.execution.steps.AbstractCaptureStateBeforeExecutionStep.execute(AbstractCaptureStateBeforeExecutionStep.java:43)
	at org.gradle.internal.execution.steps.AbstractSkipEmptyWorkStep.executeWithNonEmptySources(AbstractSkipEmptyWorkStep.java:125)
	at org.gradle.internal.execution.steps.AbstractSkipEmptyWorkStep.execute(AbstractSkipEmptyWorkStep.java:56)
	at org.gradle.internal.execution.steps.AbstractSkipEmptyWorkStep.execute(AbstractSkipEmptyWorkStep.java:36)
	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsStartedStep.execute(MarkSnapshottingInputsStartedStep.java:38)
	at org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:36)
	at org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:23)
	at org.gradle.internal.execution.steps.HandleStaleOutputsStep.execute(HandleStaleOutputsStep.java:75)
	at org.gradle.internal.execution.steps.HandleStaleOutputsStep.execute(HandleStaleOutputsStep.java:41)
	at org.gradle.internal.execution.steps.AssignMutableWorkspaceStep.lambda$execute$0(AssignMutableWorkspaceStep.java:35)
	at org.gradle.api.internal.tasks.execution.TaskExecution$4.withWorkspace(TaskExecution.java:289)
	at org.gradle.internal.execution.steps.AssignMutableWorkspaceStep.execute(AssignMutableWorkspaceStep.java:31)
	at org.gradle.internal.execution.steps.AssignMutableWorkspaceStep.execute(AssignMutableWorkspaceStep.java:22)
	at org.gradle.internal.execution.steps.ChoosePipelineStep.execute(ChoosePipelineStep.java:40)
	at org.gradle.internal.execution.steps.ChoosePipelineStep.execute(ChoosePipelineStep.java:23)
	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.lambda$execute$2(ExecuteWorkBuildOperationFiringStep.java:67)
	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:67)
	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:39)
	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:46)
	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:34)
	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:48)
	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:35)
	at org.gradle.internal.execution.impl.DefaultExecutionEngine$1.execute(DefaultExecutionEngine.java:61)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:127)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:116)
	at org.gradle.api.internal.tasks.execution.ProblemsTaskPathTrackingTaskExecuter.execute(ProblemsTaskPathTrackingTaskExecuter.java:40)
	at org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
	at org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:74)
	at org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:210)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:205)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:67)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:60)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:167)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:60)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:54)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
	at org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:42)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:331)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:318)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.lambda$execute$0(DefaultTaskExecutionGraph.java:314)
	at org.gradle.internal.operations.CurrentBuildOperationRef.with(CurrentBuildOperationRef.java:85)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:314)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:303)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:459)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:376)
	at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
	at org.gradle.internal.concurrent.AbstractManagedExecutor$1.run(AbstractManagedExecutor.java:48)


Deprecated Gradle features were used in this build, making it incompatible with Gradle 9.0.

You can use '--warning-mode all' to show the individual deprecation warnings and determine if they come from your own scripts or plugins.

For more on this, please refer to https://docs.gradle.org/8.13/userguide/command_line_interface.html#sec:command_line_warnings in the Gradle documentation.

BUILD FAILED in 5m 53s
1066 actionable tasks: 610 executed, 456 from cache
~~~
