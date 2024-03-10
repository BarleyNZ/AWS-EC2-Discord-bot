# AWS EC2 Controller Discord Bot
>Updated for 2023 by Mike Barley for new versions of Boto3 and Discord. @jakebox and @leobeosab did the work

Control an EC2 instance from discord - used for a mincreaft server.

## Requirements
* AWS IAM Role (Access Key & Secret)
* Python 3 and pip3
### Packages
* AWS CLI: `pip3 install awscli `
* AWS BOTO library: `pip3 install boto3`
* Discord Bot library: `pip3 install discord`
* Dotenv library: `pip3 install python-dotenv`

## Usage | Installation
1. Install and setup the required tools above
2. **Setup AWS CLI with `aws configure`**
3. Go to Discord's developer site and setup a bot [here](https://discordapp.com/developers)
4. Clone this repo into a desired folder
5. Fill in AWS EC2 instance ID and Discord bot token in `.env` - see `.env.example`.
7. `python3 bot.py` :)

For easy and reliable usage I recommend using upstart to restart on error and start on system startup