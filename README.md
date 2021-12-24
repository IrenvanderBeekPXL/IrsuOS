# IrsuOS
## THIS IS A SCRIPT TO BUILD IRSUOS USING CUBIC. DO NOT INSTALL THIS ON A USB STICK OR DVD. USE RELEASE FILES FROM THE RELEASE LINK

IrsuOS is an experiment run by youtuber Irsu85 (IrenvanderBeekPXL) to make Linux easy to use for gamers and streamers. I am currently working on Alpha, seeing which features I want.

If you want to build yourself, there are extra things you need to change. Those changes are explained at the end of the changescript file.

# How to build
(also when testing features for pull requests)
  1. Download Ubuntu Desktop 20.04 (will be changed to server later on in Alpha)
  2. Download Cubic: see https://launchpad.net/cubic
  3. Select the Ubuntu ISO in Cubic
  4. Copy the changescript to the terminal in Cubic
  5. Type "chmod +x c<Tab>" and "./c<Tab>". Press enter at each prompt (can take 10 minutes, depending on your internet and storage speed)
  6. If you get a purple screen with 2 options, select the bottem one
  7. If the bash prompt is visible again, click "Next" and let it do it's thing
  8. Select the top kernel and follow the instructions on the bottem of the changescript
  9. Click "Next", select the compression method (lz4 for Alpha & Beta, xz for Stable)
  10. Click "Next" and it will finish the ISO (can take a few minutes, depending on your CPU speed)
