# Khalti php integration

This is an initiate for easier implementation of khalti payment gateway for beginners in php.


## How to use it ?

1. Copy the file pay.php and khalti.png to your project folder
2. change `$khalti_public_key` with your api public key.
3. write code to get your product id, name , url and price
4. change `$successRedirect` variable. When payment will be success, this url will be called.
5. run your code to verify transaction after successful transaction, this can be used to update database or do more action on success. use `checkValid()` function for this.


## License

- It is free to use and mofify for any purpose. I don't take responsibility for misusage.

## Version

Currently, this system use khalti v2 api endpoints.

