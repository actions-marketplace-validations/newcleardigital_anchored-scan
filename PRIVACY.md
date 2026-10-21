# Privacy — Anchored Scan

Anchored Scan collects no data.

- It runs inside your own GitHub Actions runner and reads only your checkout.
- Its only network calls go to the GitHub API of the repository it runs in, with the
  token you give it: to list the pull request's files and to write or update its one
  comment. Nothing is sent to newcleardigital or anyone else.
- When `anchor-core.json` lists generated files, it runs the generator commands you
  wrote there, exactly as Anchored Lite does.
- The comment contains a link and a badge pointing to anchored.newcleardigital.com;
  following them is your choice.

Questions: office@newcleardigital.com · newcleardigital
