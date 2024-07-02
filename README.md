# Tutorial para Instalação dos Arquivos do AGV

Após efetuar a criação da pasta agv_ws e, dentro dela, criar a pasta src (Source), como descrito na documentação do AGV-Car
você deve efetuar a instalação/Git clone deste repositório dentro da pasta src.

Após isso voce deverá retornar na pasta agv_ws pelo comando via TERMINAL:

```
cd ..
```
Já na pasta agv_ws de o seguinte comando:
```
colcon build --symlink-install
```
Feito isso, irá buildar (instalar) as pastas da Source (src), cujas pastas agv_lince, diffdrive e serial serão instaladas na máquina. 
Com isso, o ROS2 conseguirá reconhecê-las e lançar os pacotes ROS.



