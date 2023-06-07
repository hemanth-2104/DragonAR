
# DragonAR

Welcome to the AR Dragon Experience project! This Unity-based augmented reality (AR) project utilizes the AR Foundation package to bring an interactive 3D dragon model to life on your Android device. By scanning a specific image, the dragon model will appear, and you can control its movements using a joystick.

## Prerequisites

Before getting started, make sure you have the following:

- Unity 2022.3.0f1 or later versions installed on your development machine.
- Android Studio with Android SDK installed.
- An Android device running Android 7.0 (Nougat) or later, with ARCore support.
- A compatible joystick or input device (optional but recommended).

## Getting Started

Follow the steps below to set up the project on your local machine and deploy it to your Android device:

1. Clone the repository to your local machine:

```shell
git clone https://github.com/hemanth-2104/DragonAR.git
```

2. Open Unity and click on **Open** to browse to the project directory. Select the **DragonAR** folder and click **Open**.

3. Once the project is open, navigate to the **Scenes** folder and open the **SampleScene** scene. This scene contains the main AR experience setup.

4. Connect your Android device to your development machine using a USB cable.

5. In Unity, click on **File -> Build Settings**. In the Build Settings window, select **Android** as the target platform.

6. Click on **Player Settings** to open the Player Settings window. In the **Other Settings** section, configure the following settings:
   - Set the **Package Name** to a unique identifier for your application (e.g., com.yourcompany.arDragonExperience).
   - Set the **Minimum API Level** to Android 7.0 or later.

7. In the Player Settings window, navigate to the **XR Plug-in Management** section. Enable **ARCore Supported**.

8. Make sure **USB Debugging** is Enabled in your **Android Device** (You can Enable it by going to the Developer Options in your Settings)

9. Click **Build and Run** to build the project and deploy it to your Android device.

10. Once the build process completes, the **DragonAR** will be opened on your Android device through Unity.

## ScreenShots

![enter image description here](https://lh3.googleusercontent.com/fife/APg5EObhRL9uGN8Efl-6TEZ0dl0wdYZXCIGmga0hvwBcW9j1PIH7uNLAb_eNjb8cjn6nb8w6OkPrEPqRsRSIYa1L6k67oesTAvh3Szah5lYnf-RTpscghyMruAfAbL1Kcr7eiOeoieJl0AITusaLl-OW4GH8kABCBi6Za1IISYanLDpZOjxVYGC2WOhmI_C1XsvAWvZD9XD6BWT8R8MfFJ0WSZlXjL1dShnhMF-X0lIbRbztem1X8LOxTOgAjxvpaxK87EKyBNYoAkFdpKQvVGBDGoSaDYhSVRbz_3dkxGjzSjwFOXABqZNG9nxpodO9Z-jyGtzMeN6cJClIAS23iSJq_JdW7KVScOqWxVN8MxcklmIVzESPeKKGti425epvIJMx62-PC4tjjWeBR3GnIMe8fYSt8rvwC7rZjxUmnAJ1rrSENDHh63ke7N2lej0YaxHoXcWdujdP4s3ZQyTVwQAzlHN2byGoyeXCpj4UVMUmtwHf7sD676fy6H3N7ofqe3NrBdS6BeUSbxmIU91O7G43GtSGDZqkq9upiuKLu9-21bvvZ2imWsqH0KrO9FqUv21tbtuAiYqa-jkIImv-i5twNff5LclRJfq9GWP1XFz7ObGqv6RiE9oh3PV8OXQW7MJI-le9cu9gTTHv2HQ6w1LD_jwUZBMCuJF5ghauI1y4-BygwaewamuY9q2enYROqz6z6g1u0kSCnSJF3qc_41fZwXZgvoYpmd1qEHn3sx9WjwsJNwfl9XQpHIOmWdN2HTNg0VI42LU0za3RlVhhjQtIhfrkts34bscy-Ys6FKvMFJHnoTF-25Lq7mMRo9HBVZVwJ8E15jnulbPvKKM_crCgB4G8YIl7nMdhvzIc16fsRoIMd05uGYNR9w9FO6X9aIUw_vlWfce8INSNtJ5IXgwQEBOtTysI09VXI_5CdseZOFBt12McOw9jCutTfzIcqHjepXw6HkQnEBYJLUtWiuWDsfM9THKkD59lmVXKL9XZ0XGNIJ2wpH1X8nEVuLcLyCCNP1dPe1ZMnw1JhNDBNZzufO662OBrGAG0sWAyBqDRCFS5_bJtgzbzrdIgMePHd_sQOBixZGgxXakJi2xT-oT9MWPH3VHxVlC28dESsc4V_DpYMh84vj_Zhjr7jRg96yy-VE64KBmCSmGOEbfF95covzc6B-Jzv4yg3TM_v-i_8K1-iyDruc3oeqzBhK9pbHVInb9wKP1ZBdHGZUxKwljo9VJrt7xp7ovuue50BFwIrKZuuEEWxH18qe5sMag08LMdQsJFcbVDIwtEs0X0bVmKWHNN1KiV7HhxdIHKV1_GLErnDcYdX1i0hHGNwOEloOU9yobsb4q4BlXukyGs-imV0oYCu0lH5-_FIsRj7NKyQW_5hf52HqSqtELM9g_K-27o4SLoqRaIZWKNjsuAkiNe-CTeAAzVyAwFJjqRrMdB6DOVhbh4RvuH7Ee1e2HfXTKMPfjq8ydKUjPqjdSTRTpLe4LNb4O_8YiIlAYIPgvTBjpZ5PFvBpjyH27Df0B6Ah7G2vVCVh3zcCdXgsD_EYcF6wG6SAe4XH80_aP6WMtVKieZMcsNAcv8UL9jfHrNEDEwKAJcSPpU8824K20erS_Os2bdacbCHDyPwOJ6bCVnefggdZEKL75l=w1920-h897)

 Dragon 3D Model Rendered when the Image is Triggered
 
 
![enter image description here](https://lh3.googleusercontent.com/fife/APg5EObs0ank2wCazRm-3ShQK_3S1l1-_fi7MDnE5kJ5Cx-XSy27rhcdXsc4rVn2l2g-IwW5faZOnOvmK2Te1Uq7wlUD0vN_Bls4pznMnzM1Wj7ITz7sATJXGpBM4EkQieK74F3bn_1RWTVYIzBDAMvisrTvbPRsx4OFdN4oL_6QSZNdBstXZahLFpEX07v0bok_cpg7DKiyhgtRjLDgpummhir6Ylays4iMlritWyz0oaaBzSHAEyLP6a5zitAtRroU36O06TCMg3S-A9u_78pBNi0wDYEUI1aR5KjshPCSB-S4SCxOkSGDNF5y1wiaFItmBaUPAR5bAPIMccXT7TcwvxuhflqLxU6t6bF1au-vMerAZRik0zoHdfHRfM0Ebz08zwX63B5uHO5-erG07ciEkWVuH6yzoL1eUMmYjToXvcB62DxGTknor_kOEKSCKw3MlUs44W6hXsyhp3jPAmSzw9iyl28tP0_RAoWnoZpoeqUro1JKaVl-S07ZB9akMwB82jAnpd6hwsLFmhQQwgI-WhLkPaLDkPk_zixBt2_sOG4kfZInjve4p3LVn8hs6GHTmB-2wh26hAVNXgX2NbFVKMy8jp-9EM76V0pAm46WfauUZf2hMPjbFTrgG4kunzoCvNjXz6AELlhHcuhk_0Rv3xyLB6oSQYPRPUVQ1nhPKYvsoF9ecqNhumcY1-lgOvakxQvdUNlOg0h-_Xy-vRIa6SjaFs6cIrjrlpALZoQ8W53URQxxdH9VDJgr4kFdCMO4rm8JXga1ZP4Dkqvq5piM8FAvWMAMBslvfrXtyiTTnOOWe9uqYzbcI5yypoo0hu8Z1jCHMvVwZDM87dc63W6fN28bJqnI1-cD5Cwf47AB5TbNpQvqtdUf_Wwmtvj7REZCLhp2Iyv8QDG40XmpFJXiqdVs_PsjKUX7x31cakNeLYpPJLb73ExRuaQIZ3NXfdculWKCUQW-J4_BBcgKcGFW4b-mjPOWc_44at1wFkhTyePk1J363CYco_4KYHfMP1Uh5V7LuDfJqD8I1vycOrSu2kmTeEehk-yA015mTeFO25bQodudy8J9wBIkGdI-g8Qnv0pEtTSgFyQMbpwkBB65SG7wlnpCRfoa69s0FWTAoFbxyoGDGz_yYs9gy2E1Nse5pkdPOTJzpSQrsPFqvazbwVrifnT-cWryp9WUwCHFeryX3Pj-Ds2LBwP2FaSEPN1tGRQ_zi4fkdFTu8AFTMJoGRh0lczwd9r0z-WR_fccDSLWVoGKfRP4nRWMHxaryfmwSr4mY78VUEN13aZ6muB4yLRX9o9Wfki7kjtTpmkAAQFvCjJnTeuBU01bJU-XVbLHOMS0iw4SyuIkrsskAuC2CgEq7UtYWli26kAW0npXIQZUQaFdtcg2DbOhBzmQuMiR-LabY6ZZsY6su-e9Q6osuVUP5rRwxwKanYO3Ru25lNs-poaVbDJYqs6CRu2V2O0ZNbL35jiQ6BVTtszXb8MSdTE-nMa7-aDM5AchjJsmMFTy84_Fp-iBqSki4kimXpu4ULBe9Vi7sQwh0H3YJwL_FXcUd1043INPs8wPjbilLxuq5m1-OJ4jEBkZ_jZNChLi-cQ-31XbP-D2yfVewJKJZQJBYQi6NOXwJ-btnd8c3BSV9LbwnjzK=w1920-h897)

You Can Move the 3D Model using the Joystick

