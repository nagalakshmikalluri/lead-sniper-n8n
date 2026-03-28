Logic Log

To handle GitHub API rate limits, I limited the number of results using the per_page=5 query parameter. This reduces the number of API calls per execution and helps prevent hitting GitHub’s rate limits. Additionally, using a scheduled trigger ensures controlled and spaced API requests.
