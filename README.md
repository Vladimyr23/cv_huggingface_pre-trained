# cv_huggingface_pre-trained
Image classification with pre-trained models from https://huggingface.co/
Here you can find the attempt to recognise a cotton harvester image using pre-trained models from https://huggingface.co/.
I tried 4 different models and returned the top result to the Jupyter notebook provided here.
**'google/vit-base-patch16-224'** model predicted the image as a mosque. Data from the ‘haggingface’ online classifier:<br /> mosque - 36.5%, <br />spotlight, spot - 6.1%,<br /> stage - 4.5%,<br /> dome - 3.1%, <br />palace -2.8%.<br />
**'microsoft/beit-base-patch16-224-pt22k-ft22k'** model predicted the image as a baseball_club, ball_club, club, nine.  Data from the ‘haggingface’ online classifier: <br />baseball_club, ball_club, club, nine - 6.27%,<br /> swastika, Hakenkreuz - 2.8%, <br />grassland - 2.7%,<br /> stadium, bowl, arena, sports_stadium - 1.6%, <br />football_stadium - 1.6%.<br />
**"microsoft/resnet-50"** model predicted the image as a stage. Data from the ‘haggingface’ online classifier:<br />stage - 100.0%, <br />loudspeaker, speaker, speaker unit, loudspeaker system, speaker system - 0%,<br /> spotlight, spot - 0%,<br />theater curtain, theatre curtain - 0%, <br />garbage truck, dustcart - 0%.<br />
**"nvidia/mit-b0"** model predicted the image as a stage. Data from the ‘haggingface’ online classifier:<br /> stage - 12.4%, <br />spotlight, spot - 4.1%,<br /> torch - 2.1%,<br /> chain mail, ring mail, mail, chain armor, chain armour, ring armor, ring armour - 1.9%, <br />harvester, reaper - 1.9%.<br />
