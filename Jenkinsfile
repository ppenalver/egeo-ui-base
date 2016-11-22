@Library('libpipelines@feature/multibranch') _

hose {
    EMAIL = 'front'
    MODULE = 'egeo-ui-base'
    DEVTIMEOUT = 30
    RELEASETIMEOUT = 30
    REPOSITORY = 'egeo-ui-base'
        
    DEV = { config ->
    
        doCompile(config)
        doUT(config)
        doDeploy(config)
    }
}