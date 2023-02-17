# laboratorio-8
Características de la onda senoidal
# OBJETIVOS

**Objetivo general**

El funcionamiento y comportamiento de la onda senoidal y los valores que abarca gráfica y numéricamente se verifican experimentalmente midiendo el dispositivo y la correcta colocación de cada componente.

**Objetivos específicos**

En el simulador correspondiente, cree un diagrama de circuito para la verificación de datos. 

Conozca las diferentes funciones de los osciloscopios y multímetros.

# MARCO TEORICO

![Onda senoidal características](https://user-images.githubusercontent.com/116819463/219550648-2d7d8dc8-470e-4338-b5a3-4481c0ea3dc6.jpg)


# Solucion

 Elementos
 
1 Generador de Funciones

1 Osciloscopio

1 Multímetro Digital

1 Resistor de 1 kΩ

1 Resistor de 2.2 kΩ

1 Protoboard

**Pasos**

-Iniciar el simulador y seleccionar los materiales a utilizar.

-Preparar los materiales en el simulador: resistencia con cada valor, osciloscopio y la fuente de energía.

-Elaborar un circuito con los materiales con la forma indicada en la guía.

-Analice lo que ocurre con el osciloscopio en la resistencia de carga RL.

-Contestar las preguntas con cada uno de los resultados obtenidos.

**Procedimiento**

![image](https://user-images.githubusercontent.com/116819463/219545158-02fc991c-bb87-4303-8a90-0228f3711b8f.png)

Armamos el circuito de la figura:

![descarga (1)](https://user-images.githubusercontent.com/116819463/219545306-50dca567-8d3b-40f8-ab4b-bb229716aa15.png)

Conectamos nuestro osciloscopio:

![descarga](https://user-images.githubusercontent.com/116819463/219545550-a903e027-307a-4ec5-b724-0cc1ed0b7a59.png)

Analizamos la grafica senoidal que nos da el osciloscopio:

![descarga (3)](https://user-images.githubusercontent.com/116819463/219545472-58c90532-4363-4ca6-8820-7a5dbfb3bc27.png)

Division por cuadro que abarca la amplitud pico de la señal de salida:

![descarga (3)](https://user-images.githubusercontent.com/116819463/219546080-7f950197-84c7-462a-a93c-5e69cd22886c.png)

Division por cuadro abarca un ciclo completo de la señal de salida:

![descarga (3)](https://user-images.githubusercontent.com/116819463/219546370-149332f3-0769-4854-9140-18d741fe10ee.png)

Calculado el periodo:

1 Div -> 0.1 ms

4 Div -> x

x=0.1*4

Periodo = T = 0.4 ms

Calculando la frecuencia natural y angular:

f=1/T

F=1/0.4/1000

F=2500 Hz

w=2π*f

w=2π*2500

w=5000π=15707.9 rad/s

Midiendo con el Múltimetro el voltaje de salida en RL:

![descarga (2)](https://user-images.githubusercontent.com/116819463/219546479-ea8d4663-c6df-4186-b102-7efda97970fe.png)

Calculando el valor eficaz del Voltaje obtenido mediante el osciloscopio:

V_eficaz= amplitud voltaje/√2

V_eficaz= 13.5/√2

V_eficaz= 9.546 V aproximado

# Responda las siguientes preguntas:

**1-¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?**

La amplitud máxima del aumento de la señal es de aprox. 1,3 divisiones por cuadro, en el gráfico vemos que sucede lo mismo, pero para la amplitud de caída podemos decir que la amplitud máxima de la salida de la señal es de aprox. 2,6 capítulos por fotograma.

**2-¿En qué valor está posicionada la perilla VOLTS/DIV?**

La perilla de VOLTS/DIV esta en: 3

**3-¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?**

Un ciclo completo de la señal de salida abarca un aproximado de 4 divisiones por cuadrado.

**4-¿En qué valor está posicionada la perilla TIME/DIV?**

La perilla de TIME/DIV esta en: 0.1ms

**5-¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?**

Amplitud de voltaje: 13.5(V)

el ciclo cumple de 4 por lo tanto en TIME/DIV nos da el valor de 0.1ms por lo tanto nuestro periodo es

Periodo: 0.4m(s)

**6-Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.**

**2500** (Hz)

**5000π=15707.9 rad/s** (rad/s)

**7-Con el multímetro digital mida el voltaje de salida en RL:** 

El voltaje de salida en RL obtenido mediante el multímetro digital es aproximado de 9.714 V

**8-Compare el voltaje medido en el punto . y el obtenido en el punto 7 ¿Coinciden?¿Por qué?**

Uno de ellos es que el voltaje medido por el osciloscopio y el multímetro no coinciden, porque el osciloscopio tiene la capacidad de mostrar visualmente señales complejas. Por otro lado, un multímetro nos da una medida precisa de señales discretas. Hay una diferencia entre los dos en la imagen y el digital.

# Conclusiones

* Esta práctica fue muy útil porque mejoramos nuestro conocimiento del uso de osciloscopios, y a través de simulaciones aprendimos más sobre el uso de dispositivos electrónicos que usaremos en nuestra vida profesional y laboral.

* Podemos concluir que una onda sinusoidal representa el valor de un voltaje variable en un tiempo continuamente variable, denotado por la amplitud y el tiempo en un par de ejes cartesianos. De la misma manera que reaccionan de la misma manera, todas las corrientes eléctricas están diseñadas para producir campos electromagnéticos de ondas de radio.

# BIBLIOGRAFÍA

Latam, M. (2020, 6 julio). Leyes de Kirchhoff. Mecatrónica LATAM. https://www.mecatronicalatam.com/es/tutoriales/teoria/leyes-de-kirchhoff/

Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion.
