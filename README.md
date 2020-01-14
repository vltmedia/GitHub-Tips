# GitHub-Tips

## GitHub LFS and Unity!

Install Git LFS beforehand.

### Clone a Full Unity Project Repo

```bash
$ git lfs clone http://my-repo.git # downloads 7/12 files from the latest commit
$ cd my-repo.local
$ git lfs fetch --all # downloads the remaining 5 files
$ git push http://new-remote.git master
```

