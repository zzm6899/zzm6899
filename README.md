# Zac Morgan

I’m a Data Science Engineer and freelance photographer. After I stopped using Lightroom Classic, I missed its photo import workflow. I built my own importer, and it became Keptra.

[LinkedIn](https://www.linkedin.com/in/zacmorgan1/)

## What I’ve learned by building

- **Python and SQL.** For my thesis, I wrote [experiments on extracting structured data from receipts](https://github.com/zzm6899/receipt-ocr-lab/tree/main/research). I built [Receipt OCR Lab](https://github.com/zzm6899/receipt-ocr-lab) to see where Tesseract found words on the page and how long it took. In [ArcadeTracker](https://github.com/zzm6899/ArcadeTracker), I used Python and SQLite to keep a history of Australian arcade card balances and make them easy to check in Discord.
- **TypeScript and Electron.** Building the [original photo importer](https://github.com/zzm6899/autophotoimporter) taught me how to detect memory cards and read EXIF metadata. Its [import engine](https://github.com/zzm6899/autophotoimporter/blob/main/src/main/services/import-engine.ts) can skip duplicates when copying files.
- **Cloudflare and self-hosting.** I use Cloudflare for DNS and HTTPS, and Docker Compose to run services on TrueNAS. The [OCR Lab GitHub Actions workflow](https://github.com/zzm6899/receipt-ocr-lab/blob/main/.github/workflows/container.yml) runs the Python tests before building and publishing the Docker image.

I’ve also completed the GitHub Skills courses on [GitHub Pages](https://github.com/zzm6899/skills-github-pages) and [code scanning with CodeQL](https://github.com/zzm6899/skills-introduction-to-codeql).

## Projects you can try

- **[Keptra](https://github.com/zzm6899/Keptra)** lets me compare shots and choose keepers before copying a card. It analyses photos locally and can organise, back up and verify the imported files. [Explore Keptra](https://keptra.z2hs.au/) or [download it for Windows or macOS](https://keptra.z2hs.au/download.html).
- **[Sessionry](https://github.com/zzm6899/Sessionry)** covers the work around a shoot. Clients pick favourites from watermarked proofs, and I can manage bookings, deliver galleries and send invoices from the same workspace. [Try the proofing demo](https://book.zacmclients.photos/demo/proofing) or [explore studio access](https://book.zacmclients.photos/buy).
- **[UTS Taekwondo](https://www.utstkd.org.au/)** has a public timetable and sign-up page. I built the member portal to handle memberships and class passes, and to let coaches take attendance and log hours. Download and open the [demo HTML](docs/utstkd/index.html) to book a class, take roll call or update the timetable with fictional records.
- **[Flickr Manager](https://github.com/zzm6899/flickr-manager)** came from a problem I kept running into with large Flickr albums: finding a photo by its title. I use it to search one album at a time, move and reorder photos, and upload whole folders.

## Background

I’m completing a Bachelor of Data Science Engineering (Honours) at the University of Technology Sydney. During my data analyst internship at KPMG Australia, I used SQL, Python and Excel to validate data for a long service leave remediation project. I also photograph sports, conventions, weddings and private events.
