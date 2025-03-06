# LeetCodee.com

Solutions to LeetCode problems with detailed explanations in multiple programming languages.

## Website Structure

The website is organized to mirror LeetCode's URL structure:

```
/
├── index.html                # Main page with problem list
├── problems/                 # All problems
│   └── problem-name/        # Individual problem folder
│       └── description/     # Problem description and solutions
│           └── index.html   # Solution page
```

## Setup Instructions

1. Fork this repository
2. Go to Settings > Pages
3. Set source to main branch
4. Set custom domain to leetcodee.com
5. Add CNAME record in your domain DNS settings:
   - Type: CNAME
   - Host: @
   - Value: your-username.github.io

## Contributing

1. Create a new problem solution:
   - Follow the URL structure: `/problems/problem-name/description/`
   - Use the template from existing solutions
   - Include solutions in all supported languages
   - Add detailed explanations

2. Update index.html:
   - Add new problem to the problem list
   - Include difficulty level
   - Add brief description

## Supported Languages

- Python
- Java
- C++
- JavaScript
- C#

## License

MIT License - feel free to use and modify the code as needed.

## Contact

For questions or suggestions, please open an issue in this repository. 