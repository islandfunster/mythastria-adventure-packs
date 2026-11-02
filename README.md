# Mythastria adventures

**Seven Isles is a free adventure.**

Adventure packs for Mythastria. They hold data only, stay separate from the engine, and load and unload while it runs.

## Seven Isles (Free Adventure)

Seven Isles is a free adventure.

- **What's here:** 70 maps with their encounters, Remix descriptions and the GM's story notes.
- **Levels:** each main map also has versions tuned for higher party levels, in `seven_isles/scenarios/levels`.
- **Characters:** none are included. Hero 1, Hero 2 and so on are only start marks; your saved characters stand beside them.

## Load it into Mythastria

1. Start Mythastria with this folder as its adventure library. Use the folder that holds `seven_isles`:

   ```bash
   py -3 engine\tools\sim_service.py --port 8840 --table isles-table\dist --adventure-packs <this folder>
   ```

2. Open `http://127.0.0.1:8840` and build or import a character on **Characters**.
3. Go to **Play an adventure**, tick your saved characters and choose Seven Isles.
4. Press **Start the adventure**. Pick a place and press **Fight here**, or use **Play live** for any map.
5. Press **End the adventure** to unload it.

## Credit

This work includes material from the System Reference Document 5.2.1 ("SRD 5.2.1") by Wizards of the Coast LLC, available at https://www.dndbeyond.com/srd. The SRD 5.2.1 is licensed under the Creative Commons Attribution 4.0 International License, available at https://creativecommons.org/licenses/by/4.0/legalcode.

## License

The adventure's own content is under the MIT License: see `LICENSE`. Material from the SRD 5.2.1 stays under the license named in the credit above.
