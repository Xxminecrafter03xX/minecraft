minecraft
=========
---- Minecraft Crash Report ----
// Shall we play a game?

Time: 12/26/13 2:50 PM
Description: Initializing game

org.lwjgl.LWJGLException: Pixel format not accelerated
	at org.lwjgl.opengl.WindowsPeerInfo.nChoosePixelFormat(Native Method)
	at org.lwjgl.opengl.WindowsPeerInfo.choosePixelFormat(WindowsPeerInfo.java:52)
	at org.lwjgl.opengl.WindowsDisplay.createWindow(WindowsDisplay.java:252)
	at org.lwjgl.opengl.Display.createWindow(Display.java:306)
	at org.lwjgl.opengl.Display.create(Display.java:848)
	at org.lwjgl.opengl.Display.create(Display.java:757)
	at org.lwjgl.opengl.Display.create(Display.java:739)
	at azi.ad(SourceFile:325)
	at azi.f(SourceFile:696)
	at net.minecraft.client.main.Main.main(SourceFile:152)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Stacktrace:
	at org.lwjgl.opengl.WindowsPeerInfo.nChoosePixelFormat(Native Method)
	at org.lwjgl.opengl.WindowsPeerInfo.choosePixelFormat(WindowsPeerInfo.java:52)
	at org.lwjgl.opengl.WindowsDisplay.createWindow(WindowsDisplay.java:252)
	at org.lwjgl.opengl.Display.createWindow(Display.java:306)
	at org.lwjgl.opengl.Display.create(Display.java:848)
	at org.lwjgl.opengl.Display.create(Display.java:757)
	at org.lwjgl.opengl.Display.create(Display.java:739)
	at azi.ad(SourceFile:325)

-- Initialization --
Details:
Stacktrace:
	at azi.f(SourceFile:696)
	at net.minecraft.client.main.Main.main(SourceFile:152)

-- System Details --
Details:
	Minecraft Version: 1.7.4
	Operating System: Windows Vista (x86) version 6.0
	Java Version: 1.7.0_40, Oracle Corporation
	Java VM Version: Java HotSpot(TM) Client VM (mixed mode, sharing), Oracle Corporation
	Memory: 4585456 bytes (4 MB) / 26808320 bytes (25 MB) up to 518979584 bytes (494 MB)
	JVM Flags: 2 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx512M
	AABB Pool Size: 0 (0 bytes; 0 MB) allocated, 0 (0 bytes; 0 MB) used
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	Launched Version: 1.7.4
	LWJGL: 2.9.1
	OpenGL: ~~ERROR~~ RuntimeException: No OpenGL context found in the current thread.
	GL Caps: 
	Is Modded: Probably not. Jar signature remains and client brand is untouched.
	Type: Client (map_client.txt)
	Resource Packs: []
	Current Language: ~~ERROR~~ NullPointerException: null
	Profiler Position: N/A (disabled)
	Vec3 Pool Size: ~~ERROR~~ NullPointerException: null
	Anisotropic Filtering: Off (1)
