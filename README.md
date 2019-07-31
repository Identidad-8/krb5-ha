# sso-krb5

        +-- README.md
        +-- kerberos_ha.yml
        +-- ansible.cfg
        +-- roles
        ¦   ¦   
        ¦   +-- kerberos
        ¦   ¦   +-- files
        ¦   ¦   ¦
        ¦   ¦   +-- templates
        ¦   ¦   ¦  
        ¦   ¦   +-- vars
        ¦   ¦       +-- main.yml
        ¦   ¦      
        ¦   +-- kerberos-clients
        ¦   ¦   ¦
        ¦   ¦   +-- tasks    
        ¦   ¦       +-- main.yml
        ¦   ¦    
        ¦   +-- kerberos-kdcs      
        ¦   ¦   ¦
        ¦   ¦   +-- tasks    
        ¦   ¦       +-- main.yml
        ¦   ¦      
        ¦   +-- kerberos-master       
        ¦   ¦   ¦
        ¦   ¦   +-- tasks    
        ¦   ¦       +-- main.yml
        ¦   ¦      
        ¦   +-- kerberos-slave       
        ¦   ¦   ¦
        ¦   ¦   +-- tasks    
        ¦   ¦       +-- main.yml
        ¦   ¦      
        ¦   +-- kerberos-trust        
        ¦   ¦   ¦
        ¦   ¦   +-- tasks    
        ¦   ¦       +-- main.yml
        ¦   ¦      
        +-- environments
            ¦      
            +-- test
                +-- hosts
                ¦  
                +-- group_vars
                    +-- all
                        +-- encrypted_passwords.yml
                        +-- kerberos.yml

