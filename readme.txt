Quick setup — if you’ve done this kind of thing before
or	
https://github.com/satyabrat929/citi-springboot-code.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# citi-springboot-code" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/satyabrat929/citi-springboot-code.git
git push -u origin main


…or push an existing repository from the command line
git remote add origin https://github.com/satyabrat929/citi-springboot-code.git
git branch -M main
git push -u origin main


Go to git bash and run the below command to generate the public key:
===================================================================
ssh-keygen -t rsa
enter
enter
enter
C:\Users\Administrator\.ssh - here id_rsa and id_rsa.pub get generated.

jaeger-all-in-one



----------------------
urls:-
-----
localhost:8080/order - 
{
    "order":
    {
        "id":26,
        "name":"Phone",
        "qty":100,
        "price":4000
    },
    "payment":{}
}

----
http://localhost:8080/actuator/refresh - refresh
----
localhost:8085/appointment/viewappointments