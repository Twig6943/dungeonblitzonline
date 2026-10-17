# Frequently Asked Questions (FAQ)

### Is this official?
No, this is a private server project created for educational and experimental purposes. It is not affiliated with or endorsed by Blue Mammoth Games.

### Is it free?
Yes. There is nothing to buy: no shop, no subscription, no paid items. Mammoth Idols and Royal Sigils are earned by playing.

### Do I need Flash Player?
No. The launcher brings its own Flash runtime and needs no browser.

### Can I run this with Flash Player?
Due to the local webserver requirement in the client and anti-cheat it's not possible.

### Is this compatible with Ruffle
Unfortunately same reasons as the previous question & depends on [this issue](https://github.com/ruffle-rs/ruffle/issues/23938)

### Can I log in with my old account?
No. The original servers and their data are gone, so every hero starts fresh. You create an account right in the login screen.

### How many friends can play together?
Parties hold up to eight heroes and share their dungeons. Monsters get tougher with every member.

### Can I play on my phone?
Yes, on Android. The APK adds two virtual sticks and on-screen buttons for skills.

### Does this have some sort of anti-cheat of its own?
Yes it does, please see [this](https://dungeonblitz.online/legal.html#privacy)

### Is this open source?
It's not. The source will be released once the creator no longer is interested in maintaining it.

### Is this self-hostable?
It's not.

### Is it possible to run the linux version with wayland/vulkan
Vulkan is possible via zink (set `MESA_LOADER_DRIVER_OVERRIDE=zink` before running the AppImage which should allow frame generation) wayland isn't possible as the pepperflash plugin requires an old version of electron which doesn't support wayland.
