# Қарақалпақша стандарт клавиатура раскладкасы

Русша стандарт клавиатура раскладкасына тийкарланып жаратылған. AEN <aen@logic.ru>.
Қарақалпақша символлар <kbd>Right Alt</kbd> клавишасы жәрдеминде териледи.

### Төмендеги символлар қосылған:

| Символ | Шорткат |
|--------|----------|
| **ў**  | <kbd>Right Alt</kbd> + <kbd>у</kbd> |
| **қ**  | <kbd>Right Alt</kbd> + <kbd>к</kbd> |
| **ң**  | <kbd>Right Alt</kbd> + <kbd>н</kbd> |
| **ғ**  | <kbd>Right Alt</kbd> + <kbd>г</kbd> |
| **ҳ**  | <kbd>Right Alt</kbd> + <kbd>х</kbd> |
| **ә**  | <kbd>Right Alt</kbd> + <kbd>а</kbd> |
| **ө**  | <kbd>Right Alt</kbd> + <kbd>о</kbd> |
| **ү**  | <kbd>Right Alt</kbd> + <kbd>и</kbd> |

## Орнатыў

1. **Ubuntu** да усы репозиториядағы `kaa` файлын `/usr/share/X11/xkb/symbols/` папкасына көшириң.
2. `/usr/share/X11/xkb/rules/evdev.xml` файлын өзгертиў ушын ашың.
    - Файлда `<layoutList>` секциясының ақырына барың (буның ушын `</layoutList>` ды излеп табың).
    - Ақырғы `</layout>` тэгинен кейин төмендегини қосың:
```xml
<layout>
  <configItem>
    <name>kaa</name>
    <shortDescription>kaa</shortDescription>
    <description>Karakalpak (Cyrillic)</description>
    <languageList>
      <iso639Id>kaa</iso639Id>
    </languageList>
  </configItem>
  <variantList/>
</layout>
```
3. `/usr/share/X11/xkb/rules/evdev.xml` файлын сақлаң.
4. Ubuntu-ды өширип-жағың.
5. Ubuntu-дың сазламаларында `Input Sources` деген жерде **Karakalpak (Cyrillic)** ти қосың.

Әўмет!

- - - -

## Karakalpak standard keyboard layout

Created based on the Russian standard keyboard. AEN <aen@logic.ru>.
The Karakalpak symbols are used with <kbd>Right Alt</kbd>.

### The following symbols were added:

| Symbol | Shortcut |
|--------|----------|
| **ў**  | <kbd>Right Alt</kbd> + <kbd>у</kbd> |
| **қ**  | <kbd>Right Alt</kbd> + <kbd>к</kbd> |
| **ң**  | <kbd>Right Alt</kbd> + <kbd>н</kbd> |
| **ғ**  | <kbd>Right Alt</kbd> + <kbd>г</kbd> |
| **ҳ**  | <kbd>Right Alt</kbd> + <kbd>х</kbd> |
| **ә**  | <kbd>Right Alt</kbd> + <kbd>а</kbd> |
| **ө**  | <kbd>Right Alt</kbd> + <kbd>о</kbd> |
| **ү**  | <kbd>Right Alt</kbd> + <kbd>и</kbd> |

## Installation

1. Copy a file `kaa` from this repository to `/usr/share/X11/xkb/symbols/` folder on **Ubuntu**.
2. Open a file `/usr/share/X11/xkb/rules/evdev.xml` in an editor.
    - Go to the end of the `<layoutList>` section (search for `</layoutList>`).
    - Add the following after the last `</layout>` tag:
```xml
<layout>
  <configItem>
    <name>kaa</name>
    <shortDescription>kaa</shortDescription>
    <description>Karakalpak (Cyrillic)</description>
    <languageList>
      <iso639Id>kaa</iso639Id>
    </languageList>
  </configItem>
  <variantList/>
</layout>
```
3. Save the file `/usr/share/X11/xkb/rules/evdev.xml`.
4. Restart your Ubuntu.
5. In `Input Sources` settings add **Karakalpak (Cyrillic)**.

That's all!


# Qaraqalpaqsha(latin) standart klaviatura raskladkası

Anglichan(us) standart klaviatura raskladkasına tiykarlanıp jaratılǵan.
Qaraqalpaqsha simvollar <kbd>Right Alt</kbd> klavishi járdeminde teriledi.

### Tómendegi simvollar qosılǵan:

| Simvol | Klavish kombinatsiyasi |
|--------|----------|
| **ú**  | <kbd>Right Alt</kbd> + <kbd>u</kbd> |
| **ń**  | <kbd>Right Alt</kbd> + <kbd>n</kbd> |
| **ǵ**  | <kbd>Right Alt</kbd> + <kbd>g</kbd> |
| **á**  | <kbd>Right Alt</kbd> + <kbd>a</kbd> |
| **ó**  | <kbd>Right Alt</kbd> + <kbd>o</kbd> |
| **ı**  | <kbd>Right Alt</kbd> + <kbd>i</kbd> |

## Ornatıw

1. **Ubuntu** da usı repozitoriyadaǵı `kaa-latin` faylın `/usr/share/X11/xkb/symbols/` papkasına `kaa` atı menen kóshiriń.
2. `/usr/share/X11/xkb/rules/evdev.xml` faylın ózgertiw ushin ashıń (ózińiz qálegen tekst editori arqali `sudo` menen ashiń).
    - Faylda `<layoutList>` bóliminiń aqırına barıń (bunıń ushın `</layoutList>` dı izlep tabıń).
    - Aqırǵı `</layout>` teginen keyin tómendegini qosıń:
```xml
<layout>
  <configItem>
    <name>kaa</name>
    <shortDescription>kaa</shortDescription>
    <description>Karakalpak (latin)</description>
    <languageList>
      <iso639Id>kaa</iso639Id>
    </languageList>
  </configItem>
  <variantList/>
</layout>
```
3. `/usr/share/X11/xkb/rules/evdev.xml` faylın saqlań.
4. Ubuntu-dı óshirip-jaǵıń.
5. Ubuntu-dıń sazlamalarinda `Input Sources` degen jerde **Karakalpak (latin)** ti qosıń.

Áwmet!

Ubuntudan basqa islewi test qilinǵan GNU/Linux distributivalari:
Fedora 39, Arch