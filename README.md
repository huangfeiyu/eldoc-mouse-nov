# eldoc-mouse-nov
Popup content of link of epub file for mouse hover when Emacs nov-mode is used.
### Demo Video
<video src="https://github.com/user-attachments/assets/f4833969-14d9-4724-bafe-0e66384f84c8" controls></video>
### Installation
1. make sure `eldoc-mouse` is installed.
``` elisp
(use-package eldoc-mouse :ensure t
  :hook (eglot-managed-mode emacs-lisp-mode nov-mode))
```
2. clone this repository.
``` bash
git clone https://github.com/huangfeiyu/eldoc-mouse-nov.git
```
3. configure `eldoc-mouse-nov`
``` elisp
(use-package eldoc-mouse-nov
  :ensure nil
  :load-path "/path/to/eldoc-mouse-nov/"
  :after (eldoc-mouse)
  :hook (nov-mode))
```

