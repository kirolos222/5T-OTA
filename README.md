# 5T-OTA
in this project ,I designed a 5T-OTA with a specific specs the design follow the gm/id methodology with a Nmos input pair 

<img width="425" height="286" alt="image" src="https://github.com/user-attachments/assets/9117e7dc-4779-4397-b7da-8068f0e57459" />

## First step(input pair design):

from spec we have gain bandwith product to be equal to 5Mhz 
 from there we can get GBW = gm/(2*pi*Cout)   ==> haing Cout dominated by Cl which is 5p so we can get gm which is  approximaly 160u siemens 
 we know that the Gain is equal to 34 db which is 50 so assuming 


## Layout:
in this layout the nmos was put in pwell which is connected to ground and pmos in a nwell connected to VDD to prevent latch up i.e. pnpn path the whole stack was put in a Dnwell for isolation

<img width="730" height="610" alt="image" src="https://github.com/user-attachments/assets/a41ed426-e484-4174-b114-243bf50a0dd7" />

## Post layout simulation:
