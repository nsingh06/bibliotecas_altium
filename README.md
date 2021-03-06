Informações do repositório
==========================

Repositório para compartilhar bibliotecas do Altium designer e mante-las atualizadas do laboratório LAPADA IFCE.

* As bibiliotecas atuais foram importadas do Eagle
* [Bibliotecas SparkFun para o Eagle](https://github.com/sparkfun/SparkFun-Eagle-Libraries)
* [Altium TechDocs](http://techdocs.altium.com/)
* [Aprenda Git](https://git-scm.com/book/pt-br/v1/Primeiros-passos)

Como Usar?
----------

Para usar as bibiliotecas clone o repositório ou baixe o .zip e instale no Altium. 
* Para instalar:
    * Abra o Altium;
    * Vá em Libraries;
    * Na aba installed vá em Install -> Install from file;
    * Vá na pasta baixada e instale os aquivos **.PCBLIB* e **.SCHLIB*;
    
* Componentes mais usados:

| Componente              | Referência          | Biblioteca     |
| ----------------------- | ------------------- | -------------- |
| Resistor 1/8W           | R-EU_0204/5         | rcl.IntLib     |
| Resistor 1/4W           | R-EU_0204/7         | rcl.IntLib     |
| Resistor SMD            | R-EU_R0805          | rcl.IntLib     |
| Capacitor Cerâmico pF   | C-EU025-025X50      | rcl.IntLib     |
| Capacitor Eletrolítico 1000 a 4700uF  | CPOL-EUE7.5-16      | rcl.IntLib     |
| Diodo retificador       | 1N4004              | diode.IntLib   |
| Diodo zenner            | ZENER-DIODEDO35Z10  | diode.IntLib   |
| Led 5mm                 | LED5MM              | led.IntLib     |
| Led 3mm                 | LED3MM              | led.IntLib     |
| Led SMD                 | LEDCHIP-LED0805     | led.IntLib     |
| Barra de pinos          | PINHD-*n*X*m*       | pinhead.IntLib |
| Borne                   | AK500/2             | con-ptr500.IntLib |
| Power Jack              | JACK-PLUG0          | con-jack.IntLib |
| Conector RJ45           | RJ45*               | con-tycoeletronics.IntLib |
| Conectores KK           | KK*                 | con-molex.IntLib |

* Atalhos utéis do Altium:
    * `[PCB+SCH]` **Space** to rotate components, change routing orientation
    * `[PCB+SCH]` **Tab** to change properties of the component you are placing
    * `[PCB+SCH]` **Page Up/Down** zooms in and out of the design
    * `[PCB+SCH]` **Ctrl+Mousewheel** zooms in/out
    * `[PCB+SCH]` **Shift+Mousewheel** pans left/right
    * `[PCB+SCH]` **Hold Shift while dragging**, makes Altium pan faster.
    * `[PCB]` **Ctrl+D** Snaps components to the grid, making it easier to align them. If you move multiple components at once, the will probbably result in the being all off the grid.
    * `[PCB]` **Ctrl+Click** on a net highlights everything connected to that net
    * `[PCB]` **Q** switches between metric and imperial units
    * `[PCB]` **P** open the place menu, P __» __T starts the interactive routing tool
    * `[PCB]` **+/-** change the routing layer, inserting a via in accordance with your current design rules.
    * `[PCB]` **Ctrl+M** measures the distance between two points
    * `[PCB]` **L** brings up the layer dialog for showing and hiding the different board layers

Como contribuir?
----------------

Para um tutorial completo visite a [Wiki](https://github.com/raquelct/bibliotecas_altium/wiki) **Em progresso*

* [Tutorial de comtribuição com Git do SparkFun](https://learn.sparkfun.com/tutorials/using-github-to-share-with-sparkfun)
* Criando novos componentes e bibliotecas:
    * [Criando componentes](http://techdocs.altium.com/display/ADOH/Creating+Library+Components+Tutorial)
    * [Criando bibliotecas](http://techdocs.altium.com/display/ADOH/Building+an+Integrated+Library)
* Editando componentes exixtentes:
    * [Atualizando componentes](http://techdocs.altium.com/display/ADOH/Keeping+Components+Up-To-Date)
    * [Criando um corpo 3D](http://techdocs.altium.com/display/ADRR/PCB_Obj-3DBody((3D+Body))_AD)
    * **Use o [3D ContentCentral](https://www.3dcontentcentral.com/Default.aspx) para baixar modelos 3D para os componentes**
    
Apenas edite um componente existente para adicionar um corpo 3D. Caso ache um erro em algum componente abra um issue ou pull request.
  
Contato
-------

* Raquel Teixeira 
    * Email: raquelct97@gmail.com
