# Get Completed Tasks

## Usage

- Create an action file in your repository, you can use [example.yml](./example.yml) as a template.
- Set the following;
  - since: the date to get completed tasks from, required, format is YYYY-MM-DDTHH:MM
  - until: the date to get completed tasks to, optional, format is YYYY-MM-DDTHH:MM
  - url: the url of the API, optional, in case version updaates!

## Notes

- The token is acquired from your repository secrets, this is passed to the action but not printed in the logs.
