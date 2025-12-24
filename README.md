# Ear X

___Control your Nothing earbuds' settings___

EarX is an application designed to manage the noise cancellation modes of your Nothing ears. Seamlessly adjust your sound experience by connecting your earbuds through Bluetooth and effortlessly switching between different settings. 

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub com.somaxa8.earx
flatpak run com.somaxa8.earx
```

## Building

```
git clone git@github.com:flathub/com.somaxa8.earx.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install com.somaxa8.earx.yml
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Rust
