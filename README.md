# Network_Infra
Router &amp; Switcher

# Graphics of Network Placement


           H   H      H   H     H   H     H   H
            \ /        \ /       \ /       \ /       SW can intermediate between R & H
             R          R         R         R         R can be Backbone to H
             |          |         |         |
        -------------------------------------------
                             |
                             R
                             |
                             V
                      External Access


# H, Hub (Layer-1)

If hubs are placed in a central location, users will need cable connections to the central location, which requires large amounts of cable, on contrast, hub closer to users, the number of hubs increased while the number of users per hub decreased.

# R, Router(Layer-3)

The number of Routers used in the network will be determined by Logical Design, if Router are used as admin demarcs(分界點) to outside networks(= internet = customer network of others), they are placed close to the demarc location of the outside network. Usually, the demark point is as known as the central location.

# SW, Switcher(Layer-2)

The SW are used as conjunction with hubs.


