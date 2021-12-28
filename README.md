# 🦑 backdoor-windows
 
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

> Simple backdoor with 0% windows detection
  
## 💻 Pré-requisitos
* Ultima versão do `Windows`
* Ultima versão do `Ruby` instalado.
  
  ## ☕ Utilização
`Clone` o repositorio usando:

```
git clone https://github.com/DioBruh/reverse-shell/
```

<span>Exporte o ip da maquina atacante para esta linha no arquivo <a href="https://github.com/DioBruh/backdoor-windows/blob/main/main.rb">main.rb</a></span>

```ruby
RHOST = '' # Aqui o seu ip.
```

<span>Caso você não saiba seu ip. Para pegar o ip da maquina:"</span>

```bash
ifconfig
```
  
<p>
  <img src="https://github.com/DioBruh/reverse-shell/blob/main/images/ifconfig.png" width="600px;">
</p>

## 💻 Inicio
Você vai precisar de 2 máquinas.

* Inicie o `arquivo` <a href="https://github.com/DioBruh/backdoor-windows/blob/main/main.rb">main.rb</a>Na maquina alvo.<br>
* Inicie uma `escuta` no seu pc escutando a porta 4444 com o comando ```nc -lvnp 4444```
* Aguarde a `Conexão` ser efetuada.

## 🤝 Colaboradores.
<table>
    <td align="center">
      <a href="https://github.com/DioBruh/">
        <img src="https://github.com/OnlyFalopas/falopas-painel/blob/main/devs/87872423.jpg" width="100px;" alt="Foto do DIO"/><br>
        <sub>
          <b>Dio Brando</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
