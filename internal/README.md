# internal

Internal core server

## app

Main init app

## module

domain module, ex: user. Contain:

    ## delivery

    protocol interface used in the app: grpc, graphql, http

    ## service

    service or business logice for app. Put interface for each domain business in this layer

    ## repository

    repository used in the app. Repository is a layer to organize data in db

## test

contain test utility and testdata

## entity

contain entities
