mutation {
    functionsCreate(
        functionId: "[FUNCTION_ID]",
        name: "[NAME]",
        runtime: "node-14.5"
    ) {
        _id
        _createdAt
        _updatedAt
        execute
        name
        enabled
        live
        logging
        runtime
        deployment
        vars {
            _id
            _createdAt
            _updatedAt
            key
            value
            resourceType
            resourceId
        }
        events
        schedule
        timeout
        entrypoint
        commands
        version
        installationId
        providerRepositoryId
        providerBranch
        providerRootDirectory
        providerSilentMode
    }
}