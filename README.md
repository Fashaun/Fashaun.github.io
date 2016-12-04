
#Setup default github pages domain name (via your account)

1. Create Empty Repository on github. (No README.md) and it's name is "$YourAccount.github.io"

2. $(git clone ${COLONE_URL})

3. $(jekyll new "${username}.github.io")

4. $(git add .)

5. $(git ci -m 'my dev site')

6. git push

7. go to https://$YourAccount.github.io/


#Problems with gem and bundle

    - gem updata --system

    - bundle update

#Build site in local 

    - $(jekyll serve)
