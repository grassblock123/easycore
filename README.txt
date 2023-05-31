=================================================================================================
							EasyCore Prview
									
Introduction:

In easyOS 2.0 , we improve the system starting up , before , we using SFT (String Fatal Task) to
staring up the system , now , we improve it to the c-El (core-EFI load) to staring up.


Mean:

The c-EL technology is mean "loaded systems from the core" , but the core we named "easycore".
the staring up is like :

Core -> EFI -> System

first , we will into bootmanager to check about all the system , and then into bootic to start 
all devices , and then turing on the EFI to staring up , and final is into the system.


[Product:beta 1 	bta-0010]
[Alpha]

=================================================================================================
