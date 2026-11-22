# Git remote check

Weekly ops check of the refs on `origin`. Output of `git ls-remote origin`, first 20 lines (the remote returned 11 lines, so this is the full output):

```
4264d9f65f54a8f5260f49a92e07f2f03ec57ad7	HEAD
4264d9f65f54a8f5260f49a92e07f2f03ec57ad7	refs/heads/main
2055572b81eb80d5f757fbb716bdeba07c1edecc	refs/heads/meghansanford487-coder-patch-1
2999f93625dd50230c14e8a40f79793ceb37df05	refs/heads/meghansanford487-coder-patch-2
7cefc097288954953c382adf7a001556ddc17216	refs/heads/meghansanford487-coder-patch-3
2055572b81eb80d5f757fbb716bdeba07c1edecc	refs/pull/1/head
4bbbee143717a8a8831b20bccb0abe083d985b75	refs/pull/1/merge
2999f93625dd50230c14e8a40f79793ceb37df05	refs/pull/2/head
e83f57ed59ab3118418c5a0893e59d7e519a0395	refs/pull/2/merge
7cefc097288954953c382adf7a001556ddc17216	refs/pull/3/head
43c0de0bd82892558a9feae3aaaceba6ee2d45dc	refs/pull/3/merge
```
