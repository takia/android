CyanogonMod (Jellybean) for HTC DNA
========================

Working:<br>
Complete running headless build <br>
Working on getting adreno GPU initialized<br>
<br>
Not Working:<br>
GPU init
<br>

Based on work by CyanogonMod team, Koush, and probably a million other people

From an internal build not synced up yet
-----  [ BEGIN DEBUG LOG ] -----

--------- beginning of /dev/log/main
I/DEBUG   (  169):     40f6df58 20342e31 72646e41 2064696f 4154454d  1.4 Android META
I/DEBUG   (  169):     40f6df68 4c47452d 00000000 00000000 00000023  -EGL........#...
I/DEBUG   (  169):     40f6df78 00000001 0000000a 00000000 00000000  ................
I/DEBUG   (  169): 
I/DEBUG   (  169): memory near sl:
I/DEBUG   (  169):     40f6df18 00000001 00000000 00000000 00000023  ............#...
I/DEBUG   (  169):     40f6df28 00000001 00000008 00000000 00000000  ................
I/DEBUG   (  169):     40f6df38 72646e41 0064696f 00000000 00000033  Android.....3...
I/DEBUG   (  169):     40f6df48 00000001 00000015 00000000 00000000  ................
I/DEBUG   (  169):     40f6df58 20342e31 72646e41 2064696f 4154454d  1.4 Android META
I/DEBUG   (  169): 
I/DEBUG   (  169): memory near ip:
I/DEBUG   (  169):     4009de74 402a939c 402a97a0 402a9b24 402adffd  ..*@..*@$.*@..*@
I/DEBUG   (  169):     4009de84 4006c86d 4006c87b 4006b28c 402a918c  m..@{..@...@..*@
I/DEBUG   (  169):     4009de94 402a5851 402a58cc 400aa1f9 400aa36d  QX*@.X*@...@m..@
I/DEBUG   (  169):     4009dea4 400aa495 400aa451 402ae1c1 402b3075  ...@Q..@..*@u0+@
I/DEBUG   (  169):     4009deb4 402b35d1 402a3aa8 402a6d34 402b088b  .5+@.:*@4m*@..+@
I/DEBUG   (  169): 
I/DEBUG   (  169): memory near sp:
I/DEBUG   (  169):     40e32c90 4022c154 402145eb 4022c108 40e32cbc  T."@.E!@.."@.,.@
I/DEBUG   (  169):     40e32ca0 00000000 00000000 df0027ad 00000000  .........'......
I/DEBUG   (  169):     40e32cb0 40f6dfa8 40f6dfac 00000000 40f6dfa8  ...@...@.......@
I/DEBUG   (  169):     40e32cc0 00000000 40f67018 00000000 402865e9  .....p.@.....e(@
I/DEBUG   (  169):     40e32cd0 40f6dfa8 00000000 40f6cf68 00000001  ...@....h..@....
I/DEBUG   (  169): 
I/DEBUG   (  169): code around pc:
I/DEBUG   (  169):     402a584c ea00acef b4504601 0600f07f f0102400  .....FP......$..
I/DEBUG   (  169):     402a585c d0050f07 2b01f811 0f07f011 d1f9b1da  .......+........
I/DEBUG   (  169):     402a586c fa82c90c faa4f246 fa83f286 faa2f346  ....F.......F...
I/DEBUG   (  169):     402a587c 2b00f386 2a00d0f4 461abf06 39073903  ...+...*...F.9.9
I/DEBUG   (  169):     402a588c 0f01f012 3101d107 7f80f412 3101bf02  .......1.......1
I/DEBUG   (  169): 
I/DEBUG   (  169): code around lr:
I/DEBUG   (  169):     40094680 fce2f7ff 21006820 f7ff3810 682bfcdf  .... h.!.8....+h
I/DEBUG   (  169):     40094690 bd386023 4606b5f8 460f4608 eea0f7fc  #`8....F.F.F....
I/DEBUG   (  169):     400946a0 b1684605 f7ff3001 b158fcb5 0410f100  .Fh..0....X.....
I/DEBUG   (  169):     400946b0 46204639 f7fc462a 2300ee4c e0025563  9F F*F..L..#cU..
I/DEBUG   (  169):     400946c0 febcf7ff 68304604 38102100 fcbef7ff  .....F0h.!.8....
D/MDnsDS  ( 2129): MDnsSdListener::Hander starting up
D/MDnsDS  ( 2129): MDnsSdListener starting to monitor
D/MDnsDS  ( 2129): Going to poll with pollCount 1
D/AndroidRuntime( 2141): 
D/AndroidRuntime( 2141): >>>>>> AndroidRuntime START com.android.internal.os.ZygoteInit <<<<<<
D/AndroidRuntime( 2141): CheckJNI is ON
I/ServiceManager(  166): service 'media.audio_flinger' died
I/ServiceManager(  166): service 'media.player' died
I/ServiceManager(  166): service 'media.camera' died
I/ServiceManager(  166): service 'media.audio_policy' died
I/Netd    ( 2267): Netd 1.0 starting
I/SurfaceFlinger( 2269): SurfaceFlinger is starting
I/SurfaceFlinger( 2269): use dithering
I/SurfaceFlinger( 2269): SurfaceFlinger's main thread ready to run. Initializing graphics H/W...
I/mediaserver( 2271): ServiceManager: 0x4165dd78
I/AudioFlinger( 2271): Using default 3000 mSec as standby time.
I/CameraService( 2271): CameraService started (pid=2271)
E/CameraService( 2271): Could not load camera HAL module
I/AudioPolicyManagerBase( 2271): loadAudioPolicyConfig() loaded /system/etc/audio_policy.conf
E/HAL     ( 2271): load: module=/system/lib/hw/audio.primary.msm8960.so
E/HAL     ( 2271): Cannot load library: link_image[1916]:  2271 could not load needed library 'libacdbloader.so' for 'audio.primary.msm8960.so' (link_image[1916]:  2271 could not load needed library 'libaudcal.so' for 'libacdbloader.so' (link_image[1916]:  2271 could not load needed library 'libdiag.so' for 'libaudcal.so' (reloc_library[1331]:  2271 cannot locate '__htclog_init_mask'...
E/HAL     ( 2271): )))
E/AudioFlinger( 2271): int android::load_audio_interface(char const*, audio_hw_device_t**) couldn't load audio hw module audio.primary (Invalid argument)
I/AudioFlinger( 2271): loadHwModule() error -22 loading module primary 
W/AudioPolicyManagerBase( 2271): could not open HW module primary
E/AudioPolicyManagerBase( 2271): Not output found for attached devices 00000003
E/AudioPolicyManagerBase( 2271): Failed to open primary output
E/AudioPolicyManagerBase( 2271): getDeviceForStrategy() speaker device not found for STRATEGY_SONIFICATION
E/AudioPolicyManagerBase( 2271): getDeviceForStrategy() speaker device not found for STRATEGY_SONIFICATION
E/AudioPolicyService( 2271): couldn't init_check the audio policy (No such device)
E/BandwidthController( 2267): runIptablesCmd(): failed /system/bin/iptables -t raw -N bw_raw_PREROUTING res=256
E/BandwidthController( 2267): runIptablesCmd(): failed /system/bin/ip6tables -t raw -N bw_raw_PREROUTING res=256
I/gralloc ( 2269): using (fd=16)
I/gralloc ( 2269): id           = msmfb44_80301
I/gralloc ( 2269): xres         = 1080 px
I/gralloc ( 2269): yres         = 1920 px
I/gralloc ( 2269): xres_virtual = 1080 px
I/gralloc ( 2269): yres_virtual = 5760 px
I/gralloc ( 2269): bpp          = 32
I/gralloc ( 2269): r            = 24:8
I/gralloc ( 2269): g            = 16:8
I/gralloc ( 2269): b            =  8:8
I/gralloc ( 2269): width        = 61 mm (449.704926 dpi)
I/gralloc ( 2269): height       = 110 mm (443.345459 dpi)
I/gralloc ( 2269): refresh rate = 60.00 Hz
D/CALCFPS ( 2269): DEBUG_CALC_FPS: 0
D/CALCFPS ( 2269): period: 10
D/CALCFPS ( 2269): ignorethresh_us: 500000
D/CALCFPS ( 2269): DEBUG_CALC_FPS: 0
D/CALCFPS ( 2269): period: 10
D/CALCFPS ( 2269): ignorethresh_us: 500000
D/libEGL  ( 2269): loaded /system/lib/egl/libEGL_adreno200.so
D/libEGL  ( 2269): loaded /system/lib/egl/libGLESv1_CM_adreno200.so
D/libEGL  ( 2269): loaded /system/lib/egl/libGLESv2_adreno200.so
E/Adreno200-GSL( 2269): <ioctl_kgsl_driver_entry:268>: open(/dev/kgsl-3d0) failed: errno 2. No such file or directory
W/libEGL  ( 2269): eglInitialize(0x1) failed (EGL_SUCCESS)
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglGetConfigs:425>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglGetConfigs:425>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglChooseConfig:594>: EGL_NOT_INITIALIZED
E/SurfaceFlinger( 2269): couldn't find an EGLConfig matching the screen format
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglCreateWindowSurface:924>: EGL_NOT_INITIALIZED
E/libEGL  ( 2269): eglQuerySurface:352 error 300d (EGL_BAD_SURFACE)
E/libEGL  ( 2269): eglQuerySurface:352 error 300d (EGL_BAD_SURFACE)
W/Adreno200-EGL( 2269): <qeglDrvAPI_eglCreateContext:2213>: EGL_NOT_INITIALIZED
E/libEGL  ( 2269): call to OpenGL ES API with no current context (logged once per thread)
F/libc    ( 2269): Fatal signal 11 (SIGSEGV) at 0x00000000 (code=1), thread 2317 (SurfaceFlinger)
I/DEBUG   (  169): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
I/DEBUG   (  169): Build fingerprint: 'htc/full_dlx/dlx:4.1.2/JZO54K/eng.drew.20121225.123937:eng/test-keys'
I/DEBUG   (  169): pid: 2269, tid: 2317, name: SurfaceFlinger  >>> /system/bin/surfaceflinger <<<
I/DEBUG   (  169): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 00000000
D/MDnsDS  ( 2267): MDnsSdListener::Hander starting up
D/MDnsDS  ( 2267): MDnsSdListener starting to monitor
D/MDnsDS  ( 2267): Going to poll with pollCount 1
I/DEBUG   (  169):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
I/DEBUG   (  169):     r4 00000000  r5 00000000  r6 ffffffff  r7 00000000
I/DEBUG   (  169):     r8 00000000  r9 40d86f08  sl 400d7b08  fp 00000000
I/DEBUG   (  169):     ip 40194e94  sp 40e86cb0  lr 4018b6a1  pc 4022d86c  cpsr 40050030
I/DEBUG   (  169):     d0  417672446c676571  d1  72436c67655f4950
I/DEBUG   (  169):     d2  646e695765746165  d3  636166727553776f
I/DEBUG   (  169):     d4  4269b9974269b991  d5  4269b6a14269b4b5
I/DEBUG   (  169):     d6  426a88a9426ae66d  d7  4269e26d426ae395
I/DEBUG   (  169):     d8  0000000043200000  d9  0000000000000000
I/DEBUG   (  169):     d10 0000000000000000  d11 0000000000000000
I/DEBUG   (  169):     d12 0000000000000000  d13 0000000000000000
I/DEBUG   (  169):     d14 0000000000000000  d15 0000000000000000
I/DEBUG   (  169):     d16 206f74206c6c6163  d17 45204c476e65704f
I/DEBUG   (  169):     d18 6977204950412053  d19 7563206f6e206874
I/DEBUG   (  169):     d20 6f6320746e657272  d21 6c2820747865746e
I/DEBUG   (  169):     d22 6e6f20646567676f  d23 7420726570206563
I/DEBUG   (  169):     d24 0000000000000000  d25 0000000000000000
I/DEBUG   (  169):     d26 0000000000000000  d27 0000000000000000
I/DEBUG   (  169):     d28 0000000000000000  d29 0000000000000000
I/DEBUG   (  169):     d30 0000000000000000  d31 0000000000000000
I/DEBUG   (  169):     scr 20000010
I/DEBUG   (  169): 
I/DEBUG   (  169): backtrace:
I/DEBUG   (  169):     #00  pc 0000e86c  /system/lib/libc.so
I/DEBUG   (  169):     #01  pc 0000f69d  /system/lib/libutils.so (android::String8::setTo(char const*)+8)
I/DEBUG   (  169):     #02  pc 00000014  [heap]
I/DEBUG   (  169): 
I/DEBUG   (  169): stack:
I/DEBUG   (  169):          40e86c70  00000000  
I/DEBUG   (  169):          40e86c74  00000000  
I/DEBUG   (  169):          40e86c78  40354154  /system/lib/libEGL.so
I/DEBUG   (  169):          40e86c7c  40e86c9c  [stack:2317]
I/DEBUG   (  169):          40e86c80  00000000  
I/DEBUG   (  169):          40e86c84  00000000  
I/DEBUG   (  169):          40e86c88  40e86c9c  [stack:2317]
I/DEBUG   (  169):          40e86c8c  4033c2cd  /system/lib/libEGL.so
I/DEBUG   (  169):          40e86c90  40354154  /system/lib/libEGL.so
I/DEBUG   (  169):          40e86c94  4033c5eb  /system/lib/libEGL.so (android::egl_display_t::HibernationMachine::decWakeCount(android::egl_display_t::HibernationMachine::WakeRefStrength)+110)
I/DEBUG   (  169):          40e86c98  40354108  /system/lib/libEGL.so
I/DEBUG   (  169):          40e86c9c  40e86cbc  [stack:2317]
I/DEBUG   (  169):          40e86ca0  00000000  
I/DEBUG   (  169):          40e86ca4  00000000  
I/DEBUG   (  169):          40e86ca8  df0027ad  
I/DEBUG   (  169):          40e86cac  00000000  
I/DEBUG   (  169):     #00  40e86cb0  400d7b48  
I/DEBUG   (  169):          ........  ........
I/DEBUG   (  169):     #01  40e86cb0  400d7b48  
I/DEBUG   (  169):          40e86cb4  400d7b4c  
I/DEBUG   (  169):          40e86cb8  00000000  
I/DEBUG   (  169):          40e86cbc  400d7b48  
I/DEBUG   (  169):          40e86cc0  00000000  
I/DEBUG   (  169):          40e86cc4  40d81018  [heap]
I/DEBUG   (  169):     #02  40e86cc8  00000000  
I/DEBUG   (  169):          40e86ccc  4020e5e9  /system/lib/libsurfaceflinger.so (android::GLExtensions::initWithGLStrings(unsigned char const*, unsigned char const*, unsigned char const*, unsigned char const*, char const*, char const*, char const*)+20)
I/DEBUG   (  169):          40e86cd0  400d7b48  
I/DEBUG   (  169):          40e86cd4  00000000  
I/DEBUG   (  169):          40e86cd8  400d7008  
I/DEBUG   (  169):          40e86cdc  00000001  
I/DEBUG   (  169):          40e86ce0  00000000  
I/DEBUG   (  169):          40e86ce4  400d7b48  
I/DEBUG   (  169):          40e86ce8  00000000  
I/DEBUG   (  169):          40e86cec  4020d23f  /system/lib/libsurfaceflinger.so (android::DisplayHardware::init(unsigned int)+1094)
I/DEBUG   (  169):          40e86cf0  00000000  
I/DEBUG   (  169):          40e86cf4  400d7b08  
I/DEBUG   (  169):          40e86cf8  40d86f08  [heap]
I/DEBUG   (  169):          40e86cfc  40d81018  [heap]
I/DEBUG   (  169):          40e86d00  00000000  
I/DEBUG   (  169):          40e86d04  00000000  
I/DEBUG   (  169): 
I/DEBUG   (  169): memory near r9:
I/DEBUG   (  169):     40d86ee8 40d86ed4 00000000 00000000 00000033  .n.@........3...
I/DEBUG   (  169):     40d86ef8 00000001 00000015 fffffff8 40d86f10  .............o.@
I/DEBUG   (  169):     40d86f08 20342e31 72646e41 2064696f 4154454d  1.4 Android META
I/DEBUG   (  169):     40d86f18 4c47452d 00007200 00000030 00000043  -EGL.r..0...C...
I/DEBUG   (  169):     40d86f28 4014bf30 402683e0 00000001 40d87000  0..@..&@.....p.@
I/DEBUG   (  169): 
I/DEBUG   (  169): memory near sl:
I/DEBUG   (  169):     400d7ae8 400d7b28 40ce1f88 00000000 00000023  ({.@...@....#...
I/DEBUG   (  169):     400d7af8 00000001 00000008 00000000 00000000  ................
I/DEBUG   (  169):     400d7b08 72646e41 0064696f 00000020 00000023  Android. ...#...
I/DEBUG   (  169):     400d7b18 00000001 0000000a 00000000 00000000  ................
I/DEBUG   (  169):     400d7b28 65726461 30326f6e 00000030 00000013  adreno200.......
I/DEBUG   (  169): 
I/DEBUG   (  169): memory near ip:
I/DEBUG   (  169):     40194e74 4023139c 402317a0 40231b24 40235ffd  ..#@..#@$.#@._#@
I/DEBUG   (  169):     40194e84 4010186d 4010187b 4010028c 4023118c  m..@{..@...@..#@
I/DEBUG   (  169):     40194e94 4022d851 4022d8cc 402711f9 4027136d  Q."@.."@..'@m.'@
I/DEBUG   (  169):     40194ea4 40271495 40271451 402361c1 4023b075  ..'@Q.'@.a#@u.#@
I/DEBUG   (  169):     40194eb4 4023b5d1 4022baa8 4022ed34 4023888b  ..#@.."@4."@..#@
I/DEBUG   (  169): 
I/DEBUG   (  169): memory near sp:
I/DEBUG   (  169):     40e86c90 40354154 4033c5eb 40354108 40e86cbc  TA5@..3@.A5@.l.@
I/DEBUG   (  169):     40e86ca0 00000000 00000000 df0027ad 00000000  .........'......
I/DEBUG   (  169):     40e86cb0 400d7b48 400d7b4c 00000000 400d7b48  H{.@L{.@....H{.@
I/DEBUG   (  169):     40e86cc0 00000000 40d81018 00000000 4020e5e9  .......@...... @
I/DEBUG   (  169):     40e86cd0 400d7b48 00000000 400d7008 00000001  H{.@.....p.@....
I/DEBUG   (  169): 
I/DEBUG   (  169): code around pc:
I/DEBUG   (  169):     4022d84c ea00acef b4504601 0600f07f f0102400  .....FP......$..
I/DEBUG   (  169):     4022d85c d0050f07 2b01f811 0f07f011 d1f9b1da  .......+........
I/DEBUG   (  169):     4022d86c fa82c90c faa4f246 fa83f286 faa2f346  ....F.......F...
I/DEBUG   (  169):     4022d87c 2b00f386 2a00d0f4 461abf06 39073903  ...+...*...F.9.9
I/DEBUG   (  169):     4022d88c 0f01f012 3101d107 7f80f412 3101bf02  .......1.......1
I/DEBUG   (  169): 
I/DEBUG   (  169): code around lr:
I/DEBUG   (  169):     4018b680 fce2f7ff 21006820 f7ff3810 682bfcdf  .... h.!.8....+h
I/DEBUG   (  169):     4018b690 bd386023 4606b5f8 460f4608 eea0f7fc  #`8....F.F.F....
I/DEBUG   (  169):     4018b6a0 b1684605 f7ff3001 b158fcb5 0410f100  .Fh..0....X.....
I/DEBUG   (  169):     4018b6b0 46204639 f7fc462a 2300ee4c e0025563  9F F*F..L..#cU..
I/DEBUG   (  169):     4018b6c0 febcf7ff 68304604 38102100 fcbef7ff  .....F0h.!.8....
D/AndroidRuntime( 2279): 
D/AndroidRuntime( 2279): >>>>>> AndroidRuntime START com.android.internal.os.ZygoteInit <<<<<<
D/AndroidRuntime( 2279): CheckJNI is ON
D/dalvikvm( 2279): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2279): Added shared lib libjavacore.so 0x0
I/ServiceManager(  166): service 'media.audio_flinger' died
I/ServiceManager(  166): service 'media.player' died
I/ServiceManager(  166): service 'media.camera' died
I/ServiceManager(  166): service 'media.audio_policy' died
I/Netd    ( 2407): Netd 1.0 starting
I/SurfaceFlinger( 2409): SurfaceFlinger is starting
I/SurfaceFlinger( 2409): use dithering
I/SurfaceFlinger( 2409): SurfaceFlinger's main thread ready to run. Initializing graphics H/W...
I/mediaserver( 2411): ServiceManager: 0x41337d78
I/AudioFlinger( 2411): Using default 3000 mSec as standby time.
I/CameraService( 2411): CameraService started (pid=2411)
E/CameraService( 2411): Could not load camera HAL module
I/AudioPolicyManagerBase( 2411): loadAudioPolicyConfig() loaded /system/etc/audio_policy.conf
E/HAL     ( 2411): load: module=/system/lib/hw/audio.primary.msm8960.so
E/HAL     ( 2411): Cannot load library: link_image[1916]:  2411 could not load needed library 'libacdbloader.so' for 'audio.primary.msm8960.so' (link_image[1916]:  2411 could not load needed library 'libaudcal.so' for 'libacdbloader.so' (link_image[1916]:  2411 could not load needed library 'libdiag.so' for 'libaudcal.so' (reloc_library[1331]:  2411 cannot locate '__htclog_init_mask'...
E/HAL     ( 2411): )))
E/AudioFlinger( 2411): int android::load_audio_interface(char const*, audio_hw_device_t**) couldn't load audio hw module audio.primary (Invalid argument)
I/AudioFlinger( 2411): loadHwModule() error -22 loading module primary 
W/AudioPolicyManagerBase( 2411): could not open HW module primary
E/AudioPolicyManagerBase( 2411): Not output found for attached devices 00000003
E/AudioPolicyManagerBase( 2411): Failed to open primary output
E/AudioPolicyManagerBase( 2411): getDeviceForStrategy() speaker device not found for STRATEGY_SONIFICATION
E/AudioPolicyManagerBase( 2411): getDeviceForStrategy() speaker device not found for STRATEGY_SONIFICATION
E/AudioPolicyService( 2411): couldn't init_check the audio policy (No such device)
E/BandwidthController( 2407): runIptablesCmd(): failed /system/bin/iptables -t raw -N bw_raw_PREROUTING res=256
E/BandwidthController( 2407): runIptablesCmd(): failed /system/bin/ip6tables -t raw -N bw_raw_PREROUTING res=256
I/gralloc ( 2409): using (fd=16)
I/gralloc ( 2409): id           = msmfb44_80301
I/gralloc ( 2409): xres         = 1080 px
I/gralloc ( 2409): yres         = 1920 px
I/gralloc ( 2409): xres_virtual = 1080 px
I/gralloc ( 2409): yres_virtual = 5760 px
I/gralloc ( 2409): bpp          = 32
I/gralloc ( 2409): r            = 24:8
I/gralloc ( 2409): g            = 16:8
I/gralloc ( 2409): b            =  8:8
I/gralloc ( 2409): width        = 61 mm (449.704926 dpi)
I/gralloc ( 2409): height       = 110 mm (443.345459 dpi)
I/gralloc ( 2409): refresh rate = 60.00 Hz
D/CALCFPS ( 2409): DEBUG_CALC_FPS: 0
D/CALCFPS ( 2409): period: 10
D/CALCFPS ( 2409): ignorethresh_us: 500000
D/CALCFPS ( 2409): DEBUG_CALC_FPS: 0
D/CALCFPS ( 2409): period: 10
D/CALCFPS ( 2409): ignorethresh_us: 500000
D/libEGL  ( 2409): loaded /system/lib/egl/libEGL_adreno200.so
D/libEGL  ( 2409): loaded /system/lib/egl/libGLESv1_CM_adreno200.so
D/libEGL  ( 2409): loaded /system/lib/egl/libGLESv2_adreno200.so
E/Adreno200-GSL( 2409): <ioctl_kgsl_driver_entry:268>: open(/dev/kgsl-3d0) failed: errno 2. No such file or directory
W/libEGL  ( 2409): eglInitialize(0x1) failed (EGL_SUCCESS)
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglGetConfigs:425>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglGetConfigs:425>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglChooseConfig:594>: EGL_NOT_INITIALIZED
E/SurfaceFlinger( 2409): couldn't find an EGLConfig matching the screen format
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglGetConfigAttrib:479>: EGL_NOT_INITIALIZED
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglCreateWindowSurface:924>: EGL_NOT_INITIALIZED
E/libEGL  ( 2409): eglQuerySurface:352 error 300d (EGL_BAD_SURFACE)
E/libEGL  ( 2409): eglQuerySurface:352 error 300d (EGL_BAD_SURFACE)
W/Adreno200-EGL( 2409): <qeglDrvAPI_eglCreateContext:2213>: EGL_NOT_INITIALIZED
E/libEGL  ( 2409): call to OpenGL ES API with no current context (logged once per thread)
F/libc    ( 2409): Fatal signal 11 (SIGSEGV) at 0x00000000 (code=1), thread 2456 (SurfaceFlinger)
D/MDnsDS  ( 2407): MDnsSdListener::Hander starting up
D/MDnsDS  ( 2407): MDnsSdListener starting to monitor
D/MDnsDS  ( 2407): Going to poll with pollCount 1
I/DEBUG   (  169): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
I/DEBUG   (  169): Build fingerprint: 'htc/full_dlx/dlx:4.1.2/JZO54K/eng.drew.20121225.123937:eng/test-keys'
I/DEBUG   (  169): pid: 2409, tid: 2456, name: SurfaceFlinger  >>> /system/bin/surfaceflinger <<<
I/DEBUG   (  169): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 00000000
D/AndroidRuntime( 2418): 
D/AndroidRuntime( 2418): >>>>>> AndroidRuntime START com.android.internal.os.ZygoteInit <<<<<<
D/AndroidRuntime( 2418): CheckJNI is ON
------ [ END DEBUG LOG ] ------
