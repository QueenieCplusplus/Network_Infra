# Network_Infra
Router &amp; Switcher

# Graphics of Network Placement


           H   H      H   H     H   H     H   H
            \ /        \ /       \ /       \ /       SW can intermediate between R & H
             R          R         R         R         R can be Backbone to H
             |          |         |         |
        -------------------------------------------
                             |
                        (Customer)
                             R
                             |
                             V
                      External Access
                             |
         -------------------------------------------
                             |
                    R, CSU, MODEMS, SONET
                           (ISP)
                      


# H, Hub (Layer-1)

If hubs are placed in a central location, users will need cable connections to the central location, which requires large amounts of cable, on contrast, hub closer to users, the number of hubs increased while the number of users per hub decreased.

# R, Router(Layer-3)

The number of Routers used in the network will be determined by Logical Design, if Router are used as admin demarcs(分界點) to outside networks(= internet = customer network of others), they are placed close to the demarc location of the outside network. Usually, the demark point is as known as the central location.

# SW, Switcher(Layer-2)

The SW are used as conjunction with hubs.

# Circuit Level Equipment

The location of Modems are good place to demarc point and boundaries outside of the building.This seems as same as isolation to put together the services in demarc.


