# MIDI-URLs
This project aims to deliver more context behind the creation and sharing habbits with MIDI files online, by connecting an URL to each individual author of MIDI files in a dataset.
<br /><br />
<b>Method</b><br />
The analysed MIDI files were gathered from all over the internet. The dataset of MIDI files analysed originated from <a href="https://github.com/albertmeronyo/MIDI-sources">the MIDI sources project from Albert Meroño</a>. Author names were extracted from copyright information in the files. Authors with less than ten files in the set were removed. The project ended up with 29493 MIDI files, each identified with a composer name. For all found names, an URL was found that contains more information about the author. This can be biographical information about the person itself, his or hers working methods, equipment such as software or keyboards, etc. The URLs can redirect to either personal web pages were MIDI files are shared or pages on other MIDI sharing sites that contain some small piece of information about the author. The information is available in Excel and jSON format.
<br /><br />
<b>Legend</b><br />
The following items are available:<br />
<ul>
  <li><b>name:</b> The extracted name of the author of the MIDI file(s)</li>
  <li><b>files:</b> The number of files the corresponding author made in the set of MIDI files.</li>
  <li><b>url:</b> The found URL containing more information about the author(s).</li>
  <li><b>originalartist:</b> Can be Y (yes) or N (no). Determines whether the author is the original composer of the musical pieces in the set of MIDI files.</li>
  <li><b>desc:</b> Short description describing what information about the author can be found in the found URL.</li>
  <li><b>srctype:</b> Determines the type of source. 1 = MIDI composer or MIDI catalogue website, 2 = hardware/software generator, 3 = original artist, 4 = publisher.</li>
</ul>


