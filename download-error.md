# Download Error
<img src="https://github.com/StreamerApp/Streamer/assets/96978272/852ef544-8c1c-416c-8ddb-dad720070d3b" alt="IMG_7838" width="300" >

- If you encounter an error while trying to download movies or TV shows, it means your installation is corrupted and you need to reinstall the app following these tips.
- If you are using a free developer account to sideload the app, we recommend using Sideloadly or AltStore to handle this for you.
- If you are using a purchased certificate or an enterprise certificate, make sure that the bundle ID is the same as the one in your certificate. You can use Esign to change the app ID.


## Modifying the Bundle Identifier with Esign

- Navigate to the settings interface in Esign and select "Certificate Management."

<img src="https://github.com/StreamerApp/Streamer/assets/96978272/0c2e491d-66fc-4dc8-b21e-002638e845f2" alt="IMG_5054" width="300" >

- Access your certificate by tapping on it.
- Copy the App ID from your certificate, which typically follows the format "xxxx.com.xxx.xxx" as illustrated in the provided screenshot. "LH28XA7T22.com.sinosig.epapp"
<img src="https://github.com/StreamerApp/Streamer/assets/96978272/6b0d3e89-a4eb-4618-b47d-aa964b0fd1dd" alt="IMG_5055" width="300" >

- Proceed to the applications section and choose Streamer.
- Initiate the signing process by selecting "Signature."
<img src="https://github.com/StreamerApp/Streamer/assets/96978272/cbe71893-dcfa-47b8-967d-eeda7e634409" alt="IMG_5055" width="300" >

- Opt for "Install after Signed" to ensure immediate installation post-signing.
<img src="https://github.com/StreamerApp/Streamer/assets/96978272/32b0472e-0a0b-4217-bd70-198578a0c9b5" alt="IMG_5055" width="300" >


- Click on "Bundle Identifier" to modify it.
- When prompted, input the new bundle ID by pasting the App ID from your certificate, omitting the initial segment (team ID) to commence with "com.xxx.xxx." e.g "com.sinosig.epapp"
<img src="https://github.com/StreamerApp/Streamer/assets/96978272/544d52e6-90ce-4d44-94ac-71fd963ece75" alt="IMG_5055" width="300" >

- Confirm the signature to finalize the process.
- Upon completion, Streamer will be promptly installed for your use.



## Full video showing the process 



https://github.com/StreamerApp/Streamer/assets/96978272/8ba76e99-06e3-4b17-8f70-fd8136a51538

