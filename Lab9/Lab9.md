## Matthew Kemenosh
## Lab 9 - YANG
### Installing WSL, pyang, and PlantUML
First I install WSL, pyang, and PlantUML
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab9/pics/pyangplantuminst.png)
### copy ~/iot/lesson9/intrusiondetection.yang to ~/demo
Then I make sure the GitHub repository is copied into my Ubuntu environment and set up my project directory.
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab9/pics/cpdemo.png)
### Run pyang to generate intrusiondetection.yin and intrusiondetection.uml
First I run cat intrusiondetection.yang to explore its contents.

![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab9/pics/idyang1.png)
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab9/pics/idyang2.png)

Then I generate my .yin file with pyang -f yin -o intrusiondetection.yin intrusiondetection.yang and explore its contents with cat intrusiondetection.yin

![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab9/pics/idyin1.png)
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab9/pics/idyin2.png)
### Run PlantUML to generate intrusiondetection.png
I run pyang ' -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef ' to generate my .uml file. I check its contents as well with '  cat intrusiondetection.uml '.
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab9/pics/iduml.png)
Then I run python3 -m plantuml intrusiondetection.uml to generate the diagram dispayed below.
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab9/pics/plantuml.png)
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab9/pics/diagram.png)


