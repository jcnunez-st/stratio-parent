@Library('libpipelines@master') _

hose {
    EMAIL = 'qa'
    MODULE = 'stratio-parent'
    DEVTIMEOUT = 20
    RELEASETIMEOUT = 20
    REPOSITORY = 'stratio-parent'
    
    DEV = { config ->        
            doPackage(config)
            doDeploy(config)
    }
}
