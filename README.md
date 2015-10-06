# doti3
Configuración para i3

Configuración de 2 pantallas. Una configuración típica sería:

(virtual screen coordinates)
     0       1366                 1366+1920
   0           A-----------------------
               |                      |
               |                      |
               |                      |
  x? B---------|         HDMI2        |
     |         |                      |
     |  eDP1   |       1920x1080      |
     |1366x768 |                      |
1080 ----------------------------------

Con A=(1366,0), B=(0,1080-768)=(0,312)


Pero, como quiero un ajuste acorde a la posición real de las
pantallas en el escritorio, un escenario ideal sería:

(virtual screen coordinates)
     0              1366                 1366+1920
   0                  A-----------------------
                      |                      |
                      |                      |
                      |                      |
                      |         HDMI2        |
  x? B----------------|       1920x1080      |
     |                |                      |
     |                |                      |
     |      eDP1      ├-----------------------
     |    1366x768    |
     |                |
1080 ------------------

A=(1366,0)
B=(0, 1080/2)=(0, 540)
