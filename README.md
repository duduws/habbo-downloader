# habbo-downloader

![GitHub release (latest by date)](https://img.shields.io/github/v/release/higoka/habbo-downloader?style=for-the-badge)
![Size](https://img.shields.io/github/languages/code-size/higoka/habbo-downloader?color=limegreen&label=size&style=for-the-badge)
![GitHub](https://img.shields.io/github/license/higoka/habbo-downloader?color=orangered&style=for-the-badge)

A tiny script to download various files directly from Habbo.

**You can add me on Discord:** `higoka#7120`

![](preview.gif)

## Prerequisites

- PHP 7.1 or higher
- OpenSSL extension enabled

## Getting Started

Just execute the correct `run` file for your os.

- `run.bat` **for Windows**
- `run.command` **for macOS**

After the initial required files have been downloaded a prompt will let you enter a command.

### Available Commands

Currently there are a total of **16 Commands** available. 
If you have ideas for **new commands or projects** please let me know.

|     Command    	|                       Description                       	|
| --------------- | ---------------------------------------------------------	|
| badges         	| Download all Habbo Badges                               	|
| furnitures     	| Download all Habbo Furnitures                           	|
| clothes        	| Download all Habbo Clothes                              	|
| effects        	| Download all Habbo Effects                              	|
| icons          	| Download all Habbo Catalogue Icons                      	|
| mp3            	| Download all Habbo MP3 Files (sound_machine_sample)     	|
| hotelview      	| Download all Habbo Hotelview Images                     	|
| ficon          	| Download all Habbo Furnitures Icons                     	|
| gamedata       	| Download all Habbo Gamedata                             	|
| habboswf       	| Download Habbo.swf                                      	|
| pets           	| Download all Habbo Pets                                 	|
| badgeparts     	| Download all Habbo Badgeparts Images                    	|
| targetedoffers 	| Download all Habbo targetedoffers Images                	|
| promo          	| Download all Habbo web_promo and web_promo_small Images 	|
| articles       	| Download all Habbo News Articles Images                 	|
| help           	| Display a list of available commands                    	|

## FAQ

### Unable to find the wrapper “https” - did you forget to enable it when you configured PHP?

**Solution**: Enable the `php_openssl` extension.  
In your php.ini search for: `extension=php_openssl` and remove the semicolon ( `;` ) then restart PHP.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
