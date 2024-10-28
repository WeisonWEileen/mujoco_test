### help !
### my environmet
- ubuntu  22.04
- MuJoCo version 3.2.4

 ### connect my  right leg is fine, however the left leg is broken. I am sure my all connect point specified in ```site1``` and ```site2```  are correct
 at the end of ```test.xml```, annotate or not annotate of ```connect_l``` to reproduce my bug

```
     <equality>
        <!-- <connect name="connect_l" site1="site_shank_l_Link" site2="site_calf_l_Link" /> -->
        <connect name="connect_r" site1="site_shank_r_Link" site2="site_calf_r_Link" />
    </equality> 
```