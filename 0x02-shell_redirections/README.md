echo Hello, world
echo "\"(Ôo)'"
cat /etc/passwd
cat /etc/passwd /etc/hosts
tail /etc/passwd
head /etc/passwd
head -n 3 iacta | tail -n 1
echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)"
ls -la > ls_cwd_content
tail -1 iacta >> iacta
find -name "*.js" -type f -delete
find -mindepth 1 -type d | wc -l
ls -t | head -10
sort | uniq -u
grep root /etc/passwd
grep -c bin /etc/passwd
grep root /etc/passwd --after-context=3
grep -v bin /etc/passwd
grep '^[[:alpha:]]' /etc/ssh/sshd_config
tr Ac Ze
tr -d cC
rev
cut -d":" -f 1,6 /etc/passwd | sort
find . -empty -printf "%f\n"
find . -type f -name "*.gif" -printf "%f\n"| rev | cut -d '.' -f2- | rev | LC_ALL=C sort -f
