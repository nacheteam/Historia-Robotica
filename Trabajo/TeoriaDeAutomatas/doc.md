# Teoría de Autómatas

En esta parte abarcaremos qué es un robot, la posible equivalencia entre robot y autómata y la evolución de estos conceptos a lo largo del tiempo. Es decir claro queda que un robot debe ser un tipo de máquina, pero la noción de lo que es una máquina ha variado significativamente a lo largo del tiempo.

Nadie dudaría sobre la veracidad de la siguiente afirmación "Un ordenador es una máquina"; sin embargo, hay una diferencia cualitativa importante entre un ordenador y un actuador mecánico, por ejemplo: una puerta automática". 

La noción de automatismo será clave para discernir qué es o no es un robot. 

## Sobre la noción de máquina

    
Partimos del concepto más simple hasta ahora mencionado, "la máquina" y de entre ellas las más sencillas de entender, las máquinas aristotélicas, siglo III A.C:

    -Simple machine, any of several devices with few or no moving parts that are used to modify motion and force in order to perform work. (Enciclopedia Britannica)


Serían: El plano inclinado, La palanca, La polea, El torno, La cuña y el tornillo. El primer enfoque de qué es una máquina está mucho más relacionado con el equilibro de fuerzas en un sistema estático que con la abstracta definición de qué cosas son máquinas que tenemos hoy en día. 

Llegamos al siglo XVI, la idea de una máquina es la de un objeto que cuyas partes distinguibles pueden ser clasificadas como una de las anteriores máquinas simples.

    - "Thus Leonardo was the first to advocate the necessity of a science of mechanisms." -  

    - " A book about the nature of mechanism must precede a book about their aplications"

>Ladislao Retti:"The Unknown Leonardo"
   
Este pensamiento hace avanzar la "ciencia de la máquina" , en los siglos anteriores el estudio de las máquinas era empírico alejado de cualquier conceptualización teórica. Es decir, el conjunto de las máquinas estaba definido por extensión. Este paso cualitativo permitió el commienzo de la conceptualización teórica de las máquinas.

Vemos el auge de este pensamiento en el mecanicismo filosófico. Encontramos grandes matemáticos como Descartes o Newton participando en esta teoría. El concepto de máquina evoluciona, una máquina será aquel objeto describible mediante las leyes de la física, la mecánica (clásica) concretamente. Vemos una definición intensiva en contraposición al pensamiento anterior. Nace con Descartes el pensamiento de que una máquina no es necesariamente un objeto artificial, considerando los animales de manera mecánica, complicada, sí, pero máquina *per se*.

La evolución del termino "maquina" se va alejando cada vez más de la aplicación concreta de la "maquina" en sí, hacia el concepto de que una máquina es aquel objeto cuyo comportamiento es determinista.

    - A machine (or mechanical device) is a mechanical structure that uses power to apply forces and control movement to perform an intended action (Wikipedia)

A nuestros ojos, la definición parece incompleta por lo pronto, pues en el conjunto que define encontraríamos las máquinas simples,los coches pero no los ordenadores. ¿Es que acaso no son máquinas? Si bien es cierto que un ordenador puede comportarse de este modo, no es una cualidad intrínseca de un ordenador. Es decir: podemos conectar un actuador mecánico para que cumpla la definición, pero no tiene mucho sentido que al desconectárselo deje de ser una máquina. 

El elemento invariante es su cualidad determinística, una máquina actúa conforme a un patrón. La categorización de un objeto físico como una máquina se produce cuando de su comportamiento se elimina el azar, se puede conocer su estado exacto después de recibir un estímulo.



### ¿Qué es un autómata?
    
Queda claro que un autómata debería ser 

- Autómata. Mecanismo técnico que realiza procesos, funciones u operaciones.
  

   - A robot is a machine —especially one programmable by a computer— capable of carrying out a complex series of actions automatically. (Wikipedia)
    - 