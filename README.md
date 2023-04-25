# #Awesome
My Personal Awesome List

## Websites
- ### AI
  - [https://scribblediffusion.com/](https://scribblediffusion.com/)
  - [https://chat.openai.com](https://chat.openai.com)
  - [https://labs.openai.com/](https://labs.openai.com/)
  - [https://freechatgpt.chat/](https://freechatgpt.chat/)
  - [https://writeout.ai](https://writeout.ai)
  - [https://github.com/LAION-AI/Open-Assistant](https://github.com/LAION-AI/Open-Assistant)
  - [https://github.com/di-sukharev/opencommit](https://github.com/di-sukharev/opencommit)
- ### Images
  - [https://shots.so/](https://shots.so/)
- ### Browsers
  - [https://arc.net/](https://arc.net/)
- ### Markdown
  - [https://github.com/typst/typst](https://github.com/typst/typst)
- ### Google
  - [https://assistant.google.com/settings/routines](https://assistant.google.com/settings/routines)
- ### Docker
  - [https://hookdeck.com/blog/post/how-run-macos-inside-docker-linux-wayland](https://hookdeck.com/blog/post/how-run-macos-inside-docker-linux-wayland)
  - [sickcodes/Docker-OSX](https://github.com/sickcodes/Docker-OSX)
  ```
  docker run -itd \
    --device /dev/kvm \
    -p 50922:10022 \
    -e AUDIO_DRIVER=pa,server=unix:/tmp/pulseaudio.socket \
    -e XDG_RUNTIME_DIR=/tmp \
    -e WAYLAND_DISPLAY=$WAYLAND_DISPLAY \
    -e NETWORKING=vmxnet3 \
    -v "/run/user/$(id -u)/pulse/native:/tmp/pulseaudio.socket" \
    -v $XDG_RUNTIME_DIR/$WAYLAND_DISPLAY:/tmp/$WAYLAND_DISPLAY  \
    -e GENERATE_SPECIFIC=true \
    -e DEVICE_MODEL="iMacPro1,1" \
    -e SERIAL="C02X9FYTHX87" \
    -e BOARD_SERIAL="C028354014NJG361M" \
    -e UUID="6C83BD0F-3EDF-4BF3-8067-173CC565A512" \
    -e MAC_ADDRESS="94:16:25:06:BF:93" \
    sickcodes/docker-osx:ventura
    ```
- ### CSS
  - [https://gradient.style/](https://gradient.style/)
- ### Blogs
  - [https://www.izzy.co/blog.html](https://www.izzy.co/blog.html)
