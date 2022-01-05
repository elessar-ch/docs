  * If there's an existing GPG key pair and you want to use it to sign commits and tags, you can display the public key using the following command
    ```shell
    $ gpg --output - --armor --export <key-email-address | key-id>
    ```
    Finally, you can [add your GPG key to your GitHub account](/articles/adding-a-new-gpg-key-to-your-github-account).
