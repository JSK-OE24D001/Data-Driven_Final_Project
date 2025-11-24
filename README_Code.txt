1. olr.nc  - Outgoing LOngwave radiation (OLR) data at global grid 2.5x2.5 degree for the period of 2010 to 2013
2. u850.nc - Zonal wind at 850 hpa pressure level at same spatial and temporal resolution as OLR
3. u200.nc - Zonal wind at 200 hpa pressure level at same spatial and temporal resolution as OLR
4. DMD_MJO_OLR.ipynb  - This notebook will perform standard DMD on MJO only with OLR data as proxy for MJO
5. DMD_MJO_OLR_U850_U200.ipynb - This notebook will perform standard DMD on MJO with OLR U850 and U200 data as proxy for MJO.
                                 THis will create the spatial pattern of the MJO with ROMs
6. WheelerPLot_MJO_OLR_U850_U200.ipynb - THis notebook will provide the standard wheeler and holton which is the actuall 
                                         representation of the MJO (if OLR + U200 + U850 together considered)