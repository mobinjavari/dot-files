<div align="left">
  <div align="left">
    <h1>MY Dot File's</h1>
    <p>my personal dot files (configurations)</p><br><br>
  </div>
  
  <div align="left">
    <h2>How install 🪧</h2>
    <p>⭕ This is how to install Manjaro. If you are using another distribution, you should know that the path of the files is different.</p><br>
  </div>
  
  <details open>
    <summary><h4>Clone Project</h4></summary>
      <p><li>Git clone</li></p>
      <pre> git clone git@github.com:mobinjavari/dot-files.git </pre>
      <p><li>Go to file</li></p>
      <pre> cd my_dot_files </pre><br>
  </details>
  
  <details open>
    <summary><h4>Oh My Zsh</h4></summary>
    <p><li>Install oy my zsh (crul)</li></p>
    <pre>sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"</pre>
    <p><li>Add config oy my zsh</li></p>
    <pre>cp .zshrc ~/</pre><br>
  </details>
  
  <details open>
    <summary><h4>Window Manager ( i3 )</h4></summary>
    <p><li>Install i3wm</li></p>
    <pre>sudo pacman -S i3wm</pre>
    <p><li>Add config for i3</li></p>
    <pre>cp -r .i3 ~/</pre><br>
  </details>
  
  <details open>
    <summary><h4>Bash</h4></summary>
    <p><li>Add config for bash</li></p>
    <pre>cp .bashrc ~/</pre><br>
  </details>
  
  <details open>
    <summary><h4>GTK Theme</a></h4></summary>
    <p><li>Add config for gtk theme <a href="https://github.com/mobinjavari/Adw-GTK-Colors">( Other configs for gtk theme )</a></li></p>
    <pre>cp .config/gtk-3.0/gtk.css ~/.config/gtk-3.0/gtk.css</pre>
    <pre>cp .config/gtk-4.0/gtk.css ~/.config/gtk-4.0/gtk.css</pre>
  </details>
</div>
