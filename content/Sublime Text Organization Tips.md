
1. **Concept of Projects and Workspaces in Sublime Text**:
   - **Projects**: Collection of directories and files. 
     - Tie a group of files and folders together into a unit.
   - **Workspaces**: ==Every project has **at least one workspace**==. 
     - Your work environment. 
     - It remembers which files you had open, the layout of your windows, unsaved changes, etc.
   
2. **Organizing Files and Folders**:
   - Go to `Project` > `Add Folder to Project` to include folders in your current workspace. This makes it easy to navigate and open files from the sidebar.
   - Use the sidebar (`View` > `Sidebar` > `Show Sidebar`) to drag and drop files and folders to organize them.

3. **Navigating to Files and Folders**:
   - Use `Ctrl+P` (or `Cmd+P` on macOS) to quickly jump between files. Start typing the name of the file you're looking for, and it will show a list of matches.
   - For navigating within a file, use `Ctrl+R` (or `Cmd+R` on macOS) to see and jump between different sections or symbols.

4. **Managing Multiple Projects**:
   - To save a project, go to `Project` > `Save Project As`, then choose a location to save the `.sublime-project` file. This makes it easy to switch between multiple projects without affecting each other.
   - You can quickly switch between projects using `Ctrl+Alt+P` (or `Cmd+Ctrl+P` on macOS).

5. **Opening Sublime Text in a Specific Folder**:
   - If you're comfortable using the terminal or command line, you can navigate to the desired folder and type `subl .` to open Sublime Text for that specific folder. This assumes you have the `subl` command available in your path.

6. **Using a Scratchpad**:
   - You can use `File` > `New File` to create a temporary scratchpad. If you decide to save it later, just go to `File` > `Save` and choose the appropriate location.

7. **Control Behavior of Opening Windows and Tabs**:
   - If you don't want Sublime to reopen all the tabs from the last session, go to `Preferences` > `Settings`, and in the right pane (your user settings), add or modify this line: `"hot_exit": false, "remember_open_files": false`.
   - This ensures that Sublime doesn't remember open tabs from previous sessions.

**Additional Tips**:

1. **Extensions**: Sublime Text has a rich ecosystem of extensions (or packages) available via [Package Control](https://packagecontrol.io/). Installing this can provide you with additional features like auto-completions, linting, theme customization, and more.
  
2. **Keyboard Shortcuts**: Familiarize yourself with Sublime's keyboard shortcuts. They'll vastly improve your efficiency. For instance:
   - `Ctrl+D` (or `Cmd+D`): Select the next instance of the word under the cursor.
   - `Ctrl+Shift+K`: Delete the current line.
   - `Alt+Shift+2`: Split view into two columns.
   
3. **Customization**: Dive into `Preferences` > `Settings` and explore the various options available. Over time, you'll find certain settings that match your workflow best.

In time, and with regular usage, you'll become more comfortable with Sublime Text and be able to utilize its power and flexibility to the fullest. The key is to practice and play around with its features to see what fits best for you.

Sublime Text, through its extensive package ecosystem, can indeed be made to mimic much of VSCode's features, including its robust sidebar functionality. Here's a list of packages and some advice to help you achieve that:

1. **Package Control**: Before anything else, ensure you have [Package Control](https://packagecontrol.io/installation) installed. It's the package manager for Sublime Text and is essential for easily adding/removing other plugins.
2. **Sidebar Enhancements**: Since you've already installed it:
   - It provides many right-click context menu options on files and folders, such as opening in Finder/Explorer, duplicating, and more.
   - After installing, right-click on any file or folder in the sidebar to see these enhanced options.

3. **A File Icon**: This package provides file-specific icons in the sidebar, similar to VSCode. It makes your sidebar visually richer and helps quickly identify file types.
4. **AdvancedNewFile**: This allows you to quickly create files and folders with a simple shortcut, `Ctrl+Alt+N` (or `Cmd+Alt+N` on macOS). It's reminiscent of the quick file/folder creation feature in VSCode.
5. **Origami**: This package allows you to create and manage panes in Sublime Text. It's not strictly sidebar-related but can enhance the overall window management experience, similar to VSCode's split editors.
6. **Terminus**: If you miss the integrated terminal from VSCode, Terminus is a great package that provides terminal integration directly into Sublime Text.
7. **LSP (Language Server Protocol)**: One of VSCode's powerful features is its IntelliSense code completion, which is backed by the Language Server Protocol. The LSP package for Sublime provides similar functionality, and you can install language-specific servers (like `LSP-pyright` for Python or `LSP-typescript` for TypeScript) for IntelliSense-like completions and features.
8. **SyncedSideBar**: This package syncs the file you're currently editing with its position in the sidebar, which can be quite useful to quickly locate a file in your project hierarchy.
9. **SublimeGit**: If you rely on Git, this package provides an interface for Git directly within Sublime Text. Though not as extensive as VSCode's Git integration, it covers many of the basic and intermediate Git tasks.
10. **Themr and Schemr**: These packages let you quickly switch between themes and color schemes, respectively, giving you the customization options you might be accustomed to with VSCode.

To make Sublime Text truly similar to VSCode, a combination of customization, theming, and keybinding changes will be required in addition to the above packages. However, do note that while Sublime can mimic many of VSCode's features, the two are distinct editors with their own strengths. Over time, you might find certain workflows where Sublime shines due to its lightweight nature and speed.

Lastly, always remember to restart Sublime Text after installing a bunch of packages to ensure they're loaded and working correctly.

Of course! Here's a curated list of key Sublime Text keyboard shortcuts, organized by category. Keep in mind that I'll mention the shortcuts for both Windows/Linux and macOS:

### File Operations:

1. **`Ctrl+N` / `Cmd+N`**: Create a new file.
2. **`Ctrl+O` / `Cmd+O`**: Open a file.
3. **`Ctrl+S` / `Cmd+S`**: Save the current file.
4. **`Ctrl+Shift+S` / `Cmd+Shift+S`**: Save the current file with a new name.

### Editing:

1. **`Ctrl+C` / `Cmd+C`**: Copy selected text.
2. **`Ctrl+V` / `Cmd+V`**: Paste text from clipboard.
3. **`Ctrl+X` / `Cmd+X`**: Cut selected text.
4. **`Ctrl+Z` / `Cmd+Z`**: Undo.
5. **`Ctrl+Shift+Z` / `Cmd+Shift+Z`**: Redo.
6. **`Ctrl+K, Ctrl+K`**: Delete from cursor to end of line.
7. **`Ctrl+Shift+K` / `Cmd+Shift+K`**: Delete entire line.

### Navigation & Search:

1. **`Ctrl+P` / `Cmd+P`**: Quick open file by name in the current project.
2. **`Ctrl+R` / `Cmd+R`**: Navigate to symbol (like function or class) in the current file.
3. **`Ctrl+G` / `Cmd+G`**: Go to line number.
4. **`Ctrl+F` / `Cmd+F`**: Find in current file.
5. **`Ctrl+Shift+F` / `Cmd+Shift+F`**: Find in all files (global search).
6. **`Ctrl+D` / `Cmd+D`**: Select next occurrence of the current word.
7. **`Ctrl+L` / `Cmd+L`**: Select the entire line.

### View & Windows:

1. **`Ctrl+K, Ctrl+B` / `Cmd+K, Cmd+B`**: Toggle the sidebar.
2. **`Alt+Shift+2` / `Cmd+Alt+2`**: Split the view into two columns.
3. **`Ctrl+K, Ctrl+Up/Down`**: Move file to a new pane.
4. **`F11`**: Full-screen mode.

### Multi-cursor & Selection:

1. **`Ctrl+Click` / `Cmd+Click`**: Add a new cursor.
2. **`Alt+F3` / `Cmd+Ctrl+G`**: Select all occurrences of the current word.
3. **`Ctrl+Shift+L` / `Cmd+Shift+L`**: Split selection into lines (for multi-editing).

### Code Manipulation:

1. **`Ctrl+/` / `Cmd+/`**: Toggle comment on current line or selection.
2. **`Ctrl+Shift+/` / `Cmd+Shift+/`**: Block comment current line or selection.
3. **`Ctrl+Shift+D` / `Cmd+Shift+D`**: Duplicate the current line or selection.
4. **`Ctrl+T` / `Cmd+T`**: Swap the characters on either side of the cursor (or swap selections).
5. **`Tab`**: Indent selection or auto-complete.
6. **`Shift+Tab`**: Dedent (un-indent) selection.

This list, though extensive, is just the tip of the iceberg. Sublime Text is renowned for its flexibility and efficiency, so as you become more familiar with it, you'll likely discover even more shortcuts that suit your personal workflow. Remember, you can also customize these shortcuts or create your own via `Preferences` > `Keybindings`.

Sure, let's delve into some more advanced and lesser-known Sublime Text shortcuts:

### Advanced Text Manipulation:

1. **`Ctrl+K, Ctrl+U` / `Cmd+K, Cmd+U`**: Convert selected text to uppercase.
2. **`Ctrl+K, Ctrl+L` / `Cmd+K, Cmd+L`**: Convert selected text to lowercase.
3. **`Ctrl+J` / `Cmd+J`**: Join the following line to the end of the current line (great for merging lines).
4. **`Ctrl+Shift+J` / `Cmd+Shift+J`**: Wrap selection with square brackets or other bracket types depending on context.
5. **`Ctrl+Shift+M` / `Cmd+Shift+M`**: Select content within the current brackets.
6. **`Ctrl+K, Ctrl+T`**: Re-indent current selection.

### Extended Navigation:

1. **`Ctrl+K, Ctrl+C`**: Move to the center of the visible area.
2. **`Ctrl+K, Ctrl+N`**: Jump forward in the jump history.
3. **`Ctrl+K, Ctrl+P`**: Jump backward in the jump history.
4. **`Ctrl+M` / `Cmd+M`**: Jump to the matching bracket.
5. **`Ctrl+U` / `Cmd+U`**: Soft undo (moves cursor back).

### Advanced Selection:

1. **`Ctrl+Shift+Space` / `Cmd+Shift+Space`**: Select scope (expands the selection outward logically, e.g., selecting a string, then the quotes, then the whole line).
2. **`Ctrl+K, Ctrl+A`**: Select to beginning of indentation or beginning of line.
3. **`Ctrl+K, Ctrl+E`**: Select to end of line.

### Tabs and Windows:

1. **`Ctrl+K, Ctrl+PageUp`**: Move the current tab left.
2. **`Ctrl+K, Ctrl+PageDown`**: Move the current tab right.
3. **`Ctrl+K, Ctrl+W`**: Close all other tabs.
4. **`Ctrl+K, Ctrl+Space`**: Set the mark (for quick movement or deletion).

### Bookmarks:

1. **`Ctrl+F2` / `Cmd+F2`**: Toggle bookmark.
2. **`F2`**: Navigate to the next bookmark.
3. **`Shift+F2`**: Navigate to the previous bookmark.
4. **`Ctrl+Shift+F2` / `Cmd+Shift+F2`**: Clear all bookmarks.

### Spell Check:

1. **`F6`**: Toggle spell check.
2. **`Ctrl+F6` / `Cmd+F6`**: Move to the next misspelled word.

### Miscellaneous:

1. **`Ctrl+K, Ctrl+V` / `Cmd+K, Cmd+V`**: Paste from history (cycles through recent clipboard items).
2. **`Ctrl+K, Ctrl+X`**: Swap with clipboard content.
3. **`Ctrl+K, Ctrl+Y` / `Cmd+K, Cmd+Y`**: Insert snippet.
4. **`Ctrl+Shift+V` / `Cmd+Shift+V`**: Paste and format (useful for code).
5. **`Ctrl+Shift+Up/Down` / `Cmd+Shift+Up/Down`**: Swap current line with the one above/below.

---

You can modify and create shortcuts via `Preferences` > `Keybindings`.
