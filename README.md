# ScoopBucket
Bucket for Scoop to install my stuff. (http://scoop.sh)

Currently contains [ROSUS](https://github.com/Guard13007/ROSUS) and
`mov2mp4` which is a simple script to convert MOV to MP4 using ffmpeg.

## Usage

1. Install [Scoop](http://scoop.sh/).
```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

2. Add the bucket!
```
scoop bucket add g-bucket https://github.com/Guard13007/ScoopBucket
```

3. Install all the things!
```
scoop install rosus mov2mp4
```
