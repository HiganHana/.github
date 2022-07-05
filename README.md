# HiganHana Specifications
This doc serves as a global specification for HiganHana bot development.

# Quality Assurance Measures
- require all commits to adhere to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
- require all core components with unittests (python unittest module)

# bot 
- hosted using repl.it
- 

# discord user profile
> is saved in a database structure
```
discord id = primary key
honkai_guild = literal[intent, yes, no]
honkai_id = nullable, int
genshin_id = nullable, int
other = json
honkai_hoyo_data = json
```

# Tsukika-Bot
- creates and maintains a user profile database (sqlalchemy) for discord user profile (flask api available)
- maintains a cache database
- sync database data with replit.db
- a web interface for managing HiganHana cluster


