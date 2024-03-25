Certainly! Lazygit is a fantastic tool for simplifying Git interactions through a terminal-based user interface. Let me provide you with an overview and some key features:

    Elevator Pitch:
        Git is powerful, but sometimes it feels like a powerful pain in the neck. Interactive rebasing, staging individual lines, and other tasks can be cumbersome.
        Lazygit aims to make your Git life easier by providing a straightforward terminal UI for common Git commands.

    Features:
        Stage Individual Lines: Press space on a selected line to stage it. Use v to select a range of lines or a to select the entire current hunk.
        Interactive Rebase: Press e on a commit to start an interactive rebase. You can squash, fixup, drop, edit, move commits, and more.
        Cherry-pick, Bisect, and Amend Old Commits directly from the UI.
        Filter commits based on various criteria.
        Invoke Custom Commands.
        Worktrees support.
        Rebase Magic: Apply custom patches during rebase.
        Undo actions.
        Commit Graph visualization.
        Compare Two Commits.

    Installation:
        Binary Releases: You can download pre-built binaries for your platform from the releases page1.
        Package Managers:
            Homebrew (Mac): brew install lazygit
            Void Linux: xbps-install -S lazygit
            Scoop (Windows): scoop install lazygit
            Arch Linux: yay -S lazygit
            Ubuntu: sudo apt-get install lazygit
            And more! Check the installation guide for additional options.

    Configuration:
        Lazygit uses a configuration file. On Linux, it’s usually located at ~/.config/jesseduffield/lazygit/config.yml.
        You can specify your preferred editor for the e command using the editPreset config (e.g., vscode, vim, emacs, etc.) 2.

    Contributing and Debugging:
        If you’d like to contribute or debug, check out the contributing guidelines.

Remember, lazygit isn’t my full-time job, but it’s a hefty part-time job. If you find it useful, consider sponsoring the project! 🚀

For more details, visit the official GitHub repository3. Happy Git-ing! 🍌


    Description :
        LazyGit est un projet open-source hébergé sur GitHub. Il a été créé par Jesse Duffield.
        Cet outil vous permet d’effectuer des opérations git courantes de manière plus conviviale et intuitive.

    Fonctionnalités :
        Stager des lignes individuelles : Appuyez sur la barre d’espace pour mettre en scène une ligne sélectionnée, ou appuyez sur v pour sélectionner une plage de lignes.
        Rebase interactif : Appuyez sur e sur un commit pour démarrer un rebase interactif. Vous pouvez ensuite fusionner (s), corriger (f), supprimer (d), éditer (e), monter (ctrl+i) ou descendre (ctrl+j) des commits dans le fichier TODO avant de continuer le rebase.
        Cherry-pick, Bisect, Nuke the working tree, Amend an old commit, Filter, Invoke a custom command, Worktrees, etc.

    Installation :
        Pour Ubuntu, vous pouvez installez Lazy Git avec la commande suivante :

        sudo apt-get install lazygit

        Pour d’autres distributions, vous pouvez consulter les instructions d’installation sur la page GitHub.

    Contribuer :
        Si vous souhaitez contribuer au projet, consultez la section Contributing sur GitHub.

    Remarque :
        LazyGit n’est pas mon travail à temps plein, mais c’est un projet auquel je consacre beaucoup de temps. Si vous souhaitez soutenir le projet, envisagez de me sponsoriser sur GitHub.

