@Library("TestLibrary@main") _
config = [:]
config["components"] = [
                "s3": [],
                "apig": [],
                "lambda": [ [ "name": "lambda1", "repo": "repo_uri", "module": "derived_domains", "params": [:]]
                ]
        ]






log("from Jenkinsfile")
plan(config)
