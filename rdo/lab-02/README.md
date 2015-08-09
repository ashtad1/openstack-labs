# Lab 2 - Devstack Horizon Interface

  Lab Objectives:

  0. Become familiar with the OpenStack Horizon Interface
  0. Launch an instance from the Horizon Interface

## Add a Project:

  0. Navigate to: Identity > Project > +Create Project
     
     ![Create Project](img/horizon-create-project.png)
     ![Create Project](img/horizon-create-project2.png)
     ![Create Project](img/horizon-create-project3.png)

## Add a User:

  0. Navigate to: Identity > Users > +Create User

     ![Create User](img/horizon-create-user.png)
     ![Create User](img/horizon-create-user2.png)
     ![Create User](img/horizon-create-user3.png)

## Member Interface

  0. Logout from the `admin` account and login as `student`
  0. Explore :red_circle: TODO: table of things to find/document

## Add a Private Network

  0. Navigate to: Project > Network > Networks > +Create Network

     ![Create Network](img/create-network.png)
     ![Create Network](img/create-network2.png)
     ![Create Network](img/create-network3.png)
     ![Create Network](img/create-network4.png)

     > :white_check_mark: **Additional Info**:
     >
     > The Allocation Pools is the start,end addresses for the pools.
     > The entry form for this field does not parse spaces.
     > Example Pool: `192.168.1.100,192.168.1.120

     ![Create Network](img/create-network5.png)

## Add a Router

  0. Navigate to: Project > Network > Network Topology > +Create Router
     
     ![Create Router](img/create-router.png)
     ![Create Router](img/create-router2.png)
  
  0. Either click on "View Router Details" or choose our new router from the list on Project > Network > Routers

     ![Create Router](img/create-router3.png)

  0. Add an interface to the new router

     ![Create Router](img/create-router4.png)
     ![Create Router](img/create-router5.png)
     ![Create Router](img/create-router6.png)