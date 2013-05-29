yajsw-stable-11.05 

    Bug: WrapperJVMMain.WRAPPER_MANAGER.signalStopping() is broken
    Bug: while (true) {wrappedJavaProcess.init(); wrappedJavaProcess.start(); wrappedJavaProcess.stop() } fails to immediatly stop the application.
    Bug: NPE in WrapperManagerImpl
    Bug:  [3605341] NoClassDefFoundError: org/rzo/yajsw/srvmgr/server/Ser
    Change: WrappedProcess.start() now resets the restart counter.
