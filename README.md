# avatars4all
Live real-time avatars from your webcam in the browser. No dedicawted hardware or software installation needed. A pure Google Colab implementation for First-order-motion-model and Avatarify. 

![GUI](gonzo_gui.png)

### Based on the works: 
1. First Order Motion Model for Image Animation, https://aliaksandrsiarohin.github.io/first-order-model-website 
2. Avatarify, https://github.com/alievk/avatarify 
3. Webcam for Google Colab over Websocket, https://github.com/a2kiti/webCamGoogleColab 
4. Wav2Lip, Accurately Lip-sync Videos to Any Speech, http://bhaasha.iiit.ac.in/lipsync

### In this repository you will find: 
1. [Colab](https://colab.research.google.com/github/eyaler/avatars4all/blob/master/fomm_live.ipynb) for live real-time talking head deep-fakes from your webcam. ([j.mp/cam2head](https://j.mp/cam2head))
2. [Colab](https://colab.research.google.com/github/eyaler/avatars4all/blob/master/fomm_bibi.ipynb) for creating talking head deep-fakes (VoxCeleb model) from YouTube or other videos. ([j.mp/vid2head](https://j.mp/vid2head))
3. [Colab](https://colab.research.google.com/github/eyaler/avatars4all/blob/master/fomm_fufu.ipynb) for creating full body deep-fakes (Tai chi and fashion models) from YouTube or other videos. ([j.mp/vid2body](https://j.mp/vid2body))
4. [Colab](https://github.com/eyaler/avatars4all/blob/master/melaflefon.ipynb) for creating lip sync deep-fakes based on audio. ([j.mp/wav2lip](https://j.mp/wav2lip))

### Features:
1. The fastest purely online solution I am aware of for live real-time first-order-motion-model avatars from your webcam.
2. A new auto-calibration mode that works in real-time!
3. A new exaggeration factor to get those damn muppets to open their mouths!
4. Options to switch between avatars, including newly generated StyleGAN faces, as inspired by Avatarify, of:
- People: https://thispersondoesnotexist.com
- Man, woman, boy, girl: https://fakeface.rest
- Waifus! https://www.thiswaifudoesnotexist.net
- Forsunas! https://thisfursonadoesnotexist.com
- Muppets! https://thismuppetdoesnotexist.com (made especially for this with Doron Adler [@norod78](https://twitter.com/norod78))
5. Smart auto-pad/crop/resize to the head or body, for images and for offline videos, tuned for best results.
6. Full control of model parameters as well as zoom and buffering options in the GUI.
7. Upload your own images and videos or pull them from the web including from YouTube, etc., and optionally trim videos.
8. Visualization of facial landmarks and their alignment between source and target.
9. Download videos with original audio and framerate.
10. One click operation with Runtime -> Run all.
11. Optional Wav2Lip post processing following head animation.
 
### Reference implementations:
1. https://colab.research.google.com/github/AliaksandrSiarohin/first-order-model/blob/master/demo.ipynb 
2. https://colab.research.google.com/github/tg-bomze/Face-Image-Motion-Model/blob/master/Face_Image_Motion_Model_(Photo_2_Video)_Eng.ipynb 
3. https://colab.research.google.com/github/alievk/avatarify/blob/master/avatarify.ipynb 
4. https://colab.research.google.com/github/a2kiti/webCamGoogleColab/blob/master/webCamGoogleColab_websocketVersion.ipynb 
5. https://colab.research.google.com/github/thefonseca/colabrtc/blob/master/examples/colabrtc.ipynb 
6. https://github.com/l4rz/first-order-model/tree/master/webrtc 
7. https://gist.github.com/myagues/aac0c597f8ad0fa7ebe7d017b0c5603b
8. https://colab.research.google.com/drive/1tZpDWXz49W6wDcTprANRGLo2D_EbD5J8

### Workshops and tutorials
- 2020-05 [Generative Jam](https://www.facebook.com/events/257984605579120/?post_id=243005947076986)
- 2020-06 [Убежище / Suoja / Shelter Festival](http://suojashelter.tilda.ws/eyal_gruss)
- 2020-06 [Open Data Science Conference (ODSC)](https://aiplus.odsc.com/courses/avatars-in-zoom-for-all)
- 2020-07 [47th South Africa National Arts Festival (NAF)](https://nationalartsfestival.co.za/show/avatars-in-zoom-for-all-a-hands-on-tutorial)
- 2020-07 [16th Athens Digital Arts Festival (ADAF)](https://online.adaf.gr/stm-zoom-webinar/adaf-online-workshop-avatars-in-zoom-eyal-gruss-il)
- 2020-09 [ReclaimFutures Conference](https://reclaimfutures.org/rf2020/events/avatars-in-zoom.html)
- 2020-10 [/’fu:bar/ Glitch Art Fest̯ivalͦ](https://fubar.space/#zoomavatars)
- 2020-10 [26th International Symposium on Electronic Art (ISEA)](https://isea2020.isea-international.org/isea2020-online-program)
- 2020-11 [30th Electronic Visualisation & the Arts London (EVA)](http://www.eva-london.org/eva-london-2020)
