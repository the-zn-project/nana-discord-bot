# Nana Rebot

## Requirements
   
   <a href="https://cmake.org/" >Cmake</a>
   <a href="https://dpp.dev/" >DPP</a>

## Compilation

    mkdir build
    cd build
    cmake ..
    make -j

If DPP is installed in a different location you can specify the root directory to look in while running cmake 

    cmake .. -DDPP_ROOT_DIR=<your-path>

## Running the bot

Create a config.json in the directory above the build directory:

```json
{
"token": "your bot token here", 
}
```

Start the bot:

    cd build
    ./nana-discord-rebot

Using the bot:

