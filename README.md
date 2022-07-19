To setup skybell
Simpley copy the configuration.yaml and enter you user name and password into secrets.yaml

Update 19-07-2022
There may now be a problem with this way of integrationg SkyBell with HomeAssistant so if you get 
The error message 
‘<’ not supported between instances of ‘BinarySensorEntityDescription’ and ‘BinarySensorEntityDescription’ same as before with…
Simpley comment out the SkyBell code from your configuration.yamal and re-test.
This error started with SSH version 9.5.0 and core version 2022.7.4 

I have now move away from SkyBell for unrelated reasons, just a coincidence the error happend at the same time I was trying new tech. So I am unliky to update this in the future. If I do try it in the future I will post a new update.

References:
https://www.home-assistant.io/integrations/skybell/
