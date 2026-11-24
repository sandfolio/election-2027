# HT Elections 2027

A static Hindustan Times assembly election prototype covering seven states. Open `index.html` in a browser to preview it. The project has no build or dependency installation step. Keep `index.html` at the root of the folder you serve.

Navigation uses URL fragments, so the prototype can be hosted in a subdirectory without routing configuration. The core interface and illustrations are packaged in the HTML. External articles, video playback, video thumbnails, and some photos need internet access.

## Add to Git

For a new repository, run these commands from the extracted folder.

```sh
git init -b main
git add index.html README.md .gitignore
git commit -m "Add HT Elections 2027 prototype"
```

To send that commit to an existing empty remote, replace `YOUR_REPOSITORY_URL` with its Git URL.

```sh
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main
```

To add the prototype to an existing repository, copy the files into the chosen folder and commit using that repository's current workflow.

The prototype includes sample data, including illustrative manifesto entries and the sample announcement countdown. Constituency follows, ratings, and comments are stored in the current browser.

The party voting poll sits in Janta ki rai alongside constituency infrastructure ratings. It shows 100 labeled sample votes plus one vote saved in the current browser. Reset Poll clears that state's ballot.

Janta ki rai combines constituency infrastructure ratings submitted in the current browser. Readers can submit ratings from constituency pages. Shared totals across readers require a backend.

The infrastructure grid shows sample ratings until the first submission. Poll results identify the sample winner above the party shares.

The Constituency map timeline shows five assembly elections per state and remembers each state's last selected year in the current browser. The timeline updates the state-level seat breakdown. The underlying constituency shapes remain schematic.

My constituency lists the seats followed in this browser, including seats across states. Follow seats from the constituency directory or existing profile controls. Searching the directory for an assembly seat number allows following a seat without a named prototype profile. The dashboard shows a four-category ratings grid and a labeled sample party poll.

The state home pages include an Election schedule preview with color-coded phase rows and a sample polling-date lookup. Uttar Pradesh has seven sample phases and a sample counting date of 13 March 2027. The other states use their own sample schedules. The linked [Election Commission notices](https://www.eci.gov.in/press-releases) are the source for official announcements.

Each state homepage embeds its own two-row illustrated portrait grid above the title and statistics. The artwork is included in the HTML. The sample candidate portraits use the same muted ink-and-gouache treatment on the homepage cards and candidate profiles.

Two editorial sections follow The News. Election in focus combines a state results feature with a photo and three related guides. Across the states uses three columns, each with a lead story and a compact companion story. The sections use credited online file photography and embedded illustrations when photos are unavailable.

More from politics adds four dated politics stories with bylines and visual previews. The Columns section is followed by a six-headline In the news grid. Story links open the original HT articles. Columnist profile photography comes from [Muck Rack](https://muckrack.com/shashi-sekhar-2), [India Development Review](https://idronline.org/contributor/roshan-kishore/), and [Centre for Policy Research](https://cprindia.org/people/rahul-verma/). If a portrait is unavailable, the card shows the author’s initials.

The Election reading list adds eight numbered links. Quick reads opens four brief guides. Short videos uses a responsive portrait carousel of voter-education videos linked to their YouTube sources.
