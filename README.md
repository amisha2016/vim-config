---
title: "Vim Configuration"
author: "Amisha Budhiraja"
---

vim-config configures your vim editor and makes it more beautiful anddisplay <b>information</b> like vim mode, file name and many more.

#Installation  

- Clone this repository 
- Copy .vimrc file into your home folder.
- Open it and type :PluginInstall. It will install all Plugins in the your $HOME/.vim directory. If you are doing it in your remote server then you <span style="background-color: #d3d3d3">have to manually install the Plugins.
- If everything goes well then quit and open any file with vim editor. You will be able to see the changes.

#Usage
<table border=1>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>:Te filename</td>
    <td>It will open that file within the vim editor. You can also select file instead of typing filename. For that type :Te and then open NerdTree(Ctrl +n) and select the exact file.</td>
  </tr>
  <tr>
    <td>gt</td>
    <td>Switch between the files opened with :Te command.</td>
  </tr>
  <tr>
    <td>Ctrl + ww</td>
    <td>Switch between the files opened with :Te command.</td>
  </tr>  
  <tr>
    <td>Ctrl-P</td>
    <td>Using ctrlp.vim Plugin enable the search and then just start typing.</td>
  </tr>  
  <tr>
    <td>:sp filename</td>
    <td>Split the layout vertically. It means the vim window is divided in two parts upper and lower.</td>
  </tr>  
  <tr>
    <td>:vs filename</td>
    <td>Split the layout horizontally. It means the vim window is divided in two parts left and right.</td>
  </tr>  
  <tr>
    <td>:b buffer_number</td>
    <td>Switch to that particular buffer.</td>
  </tr>  
  <tr>
    <td>:ls</td>
    <td>List all buffers. Buffers are the files open in that vim session</td>
  </tr>  
  <tr>
    <td>Ctrl + ww</td>
    <td>Switch between the files opened with :Te command.</td>
  </tr>  
</table>
