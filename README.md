# minebot
Simpele minecraft agent 

start hem met:
node chest.js <server_ip> <server_port> <bot_master>
Server ip is bijvoorbeeld node1.justvikie.online
Server port is bijvoorbeeld 12928
Bot master is de minecraft user die alle commands kan uitvoeren, is bijvoorbeeld justthedev

📦 **Chest en Inventarisbeheer**
- `list` – Laat de items in de bot zijn inventaris zien.  
- `chest` – De bot zoekt een kist in de buurt en opent deze.  
   - In de kist kun je deze extra commando’s gebruiken:
     - `close` – Sluit de kist.  
     - `withdraw <aantal> <item>` – Haal items uit de kist.  
       - Voorbeeld: `withdraw 16 stick`  
     - `deposit <aantal> <item>` – Leg items in de kist.  
       - Voorbeeld: `deposit 32 dirt`  

- `chestminecart` – De bot zoekt naar een **chest minecart** en opent deze.  
- `dispenser` – De bot opent de dichtstbijzijnde **dispenser**.  

 🔥 **Furnace (Oven) Beheer**
- `furnace` – De bot opent de dichtstbijzijnde oven.  
   - In de oven kun je extra commando’s gebruiken:
     - `close` – Sluit de oven.  
     - `input <aantal> <item>` – Plaats items in het input-slot.  
     - `fuel <aantal> <item>` – Voeg brandstof toe.  
     - `take input` – Haal het input-item eruit.  
     - `take fuel` – Haal de brandstof eruit.  
     - `take output` – Neem het resultaat uit de oven.  

📚 **Enchantment Table Beheer**
- `enchant` – De bot zoekt een **enchantment table** en opent deze.  
   - In de enchantment table kun je extra commando’s gebruiken:
     - `close` – Sluit de enchantment table.  
     - `put <item>` – Plaats een item om te betoveren.  
     - `add lapis` – Voeg lapis lazuli toe.  
     - `enchant <nummer>` – Voer een betovering uit (1, 2 of 3).  
     - `take` – Neem het betoverde item uit de tafel.
