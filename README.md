# Who Invited the Idiot? — GitHub Pages pack

This folder contains the complete original quiz (2,915 questions), with a
microphone check added to its opening screen and home-screen app icons.

## Publish using GitHub (no coding needed)

1. Sign in at https://github.com and create a **new public repository** named
   `who-invited-the-idiot`. Leave **Add a README file** unticked.
2. On the empty repository page tap **uploading an existing file**. If the
   repository already has files, use **Add file → Upload files** instead.
   Upload **all files in this folder** to the repository's root, not the ZIP
   itself and not the enclosing folder. Keep the file named `index.html`.
3. Choose **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, choose
   **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. Once GitHub shows the published address, open
   `https://YOUR-USERNAME.github.io/who-invited-the-idiot/` in Chrome.
6. On the quiz opening screen tap **TEST MICROPHONE FIRST**, allow the
   microphone request, say "hello", and check that it heard you.
7. On Android Chrome, open the browser menu (⋮) and choose **Add to Home screen**
   or **Install app** to get an icon on your phone.

On a phone, GitHub may hide upload or Settings controls in its compact layout.
If that happens, open GitHub in Chrome and turn on **Desktop site** from Chrome's
menu while you upload and configure Pages.

The GitHub Pages publishing address becomes available after deployment; it
may take a few minutes. GitHub Pages is an HTTPS website, so it is suited to
browser microphone permissions.

## Important details

- **Browser support:** the game uses the browser's SpeechRecognition API.
  Chrome on Android is the intended choice. Microphone permission and internet
  access may be necessary. Other browsers can behave differently.
- **Backup answers:** if speech recognition isn't available, the game has its
  existing Emergency answers option in the three-dot menu.
- **Privacy:** publishing on GitHub Pages makes the quiz publicly accessible,
  and anyone can view browser-delivered HTML/JavaScript, including its questions.
  Don't upload secret material. GitHub Pages itself does not hide the source.
- **Offline:** the screen and questions can load from a local cache after one
  successful visit, but the browser's speech recognition may still need the
  internet.
- **Saved scores:** existing local scores and question history are per browser
  and web address. Scores saved from a file opened locally do not automatically
  transfer to the new GitHub Pages address.
