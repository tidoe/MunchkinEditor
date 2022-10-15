# MunchkinEditor

Create high-quality custom cards for the [Munchkin](https://munchkin.game/) card game!

For example:

<img src="https://github.com/tidoe/MunchkinEditor/blob/main/example/Sword_in_the_Stone.png" height="400"/>

(Note that I am not associated with the creators of the Munchkin game in any way.)

## Start

Download and unzip this repository and save it to a location of your choice on your computer.

Open the file `editor.html` in a browser, e.g. Google Chrome (double-clicking the file should do this).

## Use

You can see a preview of your card on the left. The card preview should display all changes immediately (or shortly after) you made them. If the preview does not refresh automatically, you can use the refresh button (🗘) at the bottom.

The topmost button switches between door cards and treasure cards. If the card preview does not switch to the correct background after you clicked on this button, just click on the refresh button.

Hopefully, the text fields are self-explaining. Note that linebreaks (by the Enter key) are only supported in the main text fields (*Text* and *Bad Stuff*). If you want a linebreak in any of the fields *Name*, *[Modify Monster]* or *[Change Level]*, you can type a *#* where a linebreak should be inserted. The other fields do not allow linebreaks.

With the button in the middle you can select an image to place on your card. The three fields below can be used to change the position and scaling of the image.

## Save/Load

If you want to save your card, click on the save button (📥) below the card preview. This will save the card as `.png` and `.html` file in your "Downloads" folder. If you do not specify a filename in the text field right left of the save button, the filename will be created from the card's name.

If you want to continue working on a card, open the saved `.html` file. This will redirect you to the MunchkinEditor and insert all the parameters of your card, except the image. You have to load the image again, but position and scaling are saved from the last time.

## Example

You can find an example for a custom treasure card (*Sword in the Stone*) in `example`. You can load and edit the card by opening `Sword_in_the_Stone.html` and loading the image `11515.png` again. (The image was downloaded from [Openclipart](#https://openclipart.org/detail/11515/rpg-map-symbols-sword-in-the-stone).)

## Resources

The font files can be downloaded [here](https://ufonts.com/fonts/quasimodo.html) and [here](https://www.wfonts.com/font/caslon-antique).
