# Ejercicio Torreta
- Copie un Modelo **tank** y lo modifique llamandole **turret** , modifique su base añadiendole un objeto 3D de un *cuadrado* al cual modifique para simular la base de una torreta, aproveche la cabeza del tanque para que simulase la torreta,
  tambien copie el material de la torreta para poder darle el mismo color.
- Luego realice una copia del script que controla el tanque enemigo **TanksNPCController** y lo renombre como **TurretNPCController** y realizar cualquier modificación.
- Dentro del script debido a que el ejercicio basicamente pedía la **torreta** no se moviese como el tanque , simplemente comente las ultimas lineas de codigo
  del metodo ***Update*** ,de este módo la torreta girara siempre a la posición donde se mueva el tanque y disparara a donde este el.

```csharp
  
        /*else
        {
            // Se non disparamos, movémonos cara adiante ao ritmo moveSpeed
            this.transform.Translate(0.0f, 0.0f, Time.deltaTime * moveSpeed);
        }*/
    }
```
