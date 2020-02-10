# Bakugan Pro Plugin for Cockatrice

Thanks for taking an interest in this little hobby project. Updates may be slow, so be warned. I'm only one girl working on this all alone, and it took several entire days to even get it where it is now.
**Disclaimer** - I don't own Bakugan, in any capacity. This was constructed via publicly available information and content and is just made to be a non-profit tool for deck building and testing.

**This is intended to be used with [Cockatrice](https://cockatrice.github.io/):**
After getting it, it'll probably download a database of Magic the Gathering cards. (Magic being the game this program was made for.)
After downloading Cockatrice, follow these steps to enabling Bakugan Pro:
  1. Open Cockatrice, it will download a database of MtG cards, hit OK and let it do its thing. This may take a bit.
  2. Restart the program. Open Card Database -> Manage Sets. Disable all sets, and then place a check mark to enable the most recent set and hit Ok.
  3. Go to Card Database -> Open Custom Sets Folder. Move one folder up into the Cockatrice root folder, close Cockatrice and merge the folders from the Bakugan Pro plugin here.
  4. Open Cockatrice once more. It will detect the new sets and ask if you wish to enable them, click yes. You can then go back into Manage Sets and disable the set you earlier enabled. At this point, Cockatrice should now only display Bakugan Pro cards.
  5. This is an optional step, but if you wish to play MtG as well, you can go into Manage Sets and enable all sets. However, if you have no intention of playing MtG via Cockatrice, I suggest you open the root Cockatrice folder, rename "Bakugan TCG.xml" to "cards.xml", move it to the root folder and click to replace the old xml when asked.

**Notice** - Unfortunately some cards seem to share names with MtG cards and this can cause conflicting issues where some cards will not show up or will be replaced with the MtG card if you choose not to replace the cards.xml database. My best suggestion is to, of course, replace the cards.xml file, but if you don't want to, the only other way to fix this is to edit the Bakugan TCG.xml with a program such as Notepad++, ctrl+F and search the card name, and add an indicator at the end of its set to differentiate it.

**Tips and Stuff**
  1. Go to Cockatrice -> Settings -> Appearance, and you can change the current theme to Bakugan TCG. This doesn't really do anything, but it looks nicer in my opinion.
  2. When building a deck, place Character Cards and BakuCores in the Sideboard. In a game, you can quickly open the Sideboard with ctrl+F3.
  3. Hold the Shift key when moving a card onto the board to place it facedown.
  4. You can use the Deck Editor's Filters to help sort through or narrow down cards. For example, "And, Color, Ventus" to display only Ventus cards, or "And Not, Type, Character" to display everything except Character Cards. You can add multiple Filters to narrow it down further. "And Type Character + And Color Haos" will only display Haos Character Cards. These filters can also be used to search card text, for example "And Text Sacrifice" will show only cards that have "Sacrifice" in its ability text.

Will update this later with more information as needed.
