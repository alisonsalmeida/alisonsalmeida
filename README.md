## Alison Almeida

### 💼 Desenvolvedor de Software
<p>Atualmente é programador backend no Laboratorio de Sistemas Embarcados dentro do centro da Pesquisa da Universidade do Estado do Amazonas.</p>

### 🕛 Melhor Horario 🕡
<p>Adora trabalhar de madrugada ao som de um bom rock, e quando nao está trabalhando está codando alguma coisa interessante, ou seja, ta sempre codando.
Ama programar e isso é bom, pois une o util ao agradavél.
</p>

```python

import asyncio

async def fun():
    while True:
        await coding()
        await asyncio.sleep(60 * 60 * 4)

async def work():
    coffe = False
    while True:
        if coffe is False:
            coffe = await do_coffe()
        
        await coding()
        await asyncio.sleep(60 * 60 * 12)

async def life(event_loop):
    """
      Com uma rotina corrida, as tarefas são assincronas
    """
    event_loop.create_task(work())
    event_loop.create_task(fun())
    
    event = asyncio.Event()
    
    await event.wait()

if __name__ == '__alison__':
    event_loop = asyncio.get_event_loop()
    asyncio.run(life(event_loop))

```
