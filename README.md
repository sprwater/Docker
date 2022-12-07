# # 安装podman-desktop

> 下载并安装flatpak
>
> 添加flathub存储库（Add the Flathub repository）
>
> 安装podman-desktop

* 安装flatpak

  ```shell
  dnf  install  flatpak  -y
  ```



* 添加flathub仓库

  ```shell
  flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
  ```

  

* 在Rocky Linux系统中安装podman-desktop

  ```shell
  flatpak install podman-desktop-0.9.1.flatpak
  ```

  
