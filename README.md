# violetkuma

Just my personal Uptime Kuma theme.

## Installation

How to install the theme.

1. Go to the your status page and click `Edit Status Page`, you need to be logged on the dashboard for this button to appear.

1. Paste this HTML code into the Footer Text input:

   ```html
   <ul class="circles">
     <li></li>
     <li></li>
     <li></li>
     <li></li>
     <li></li>
     <li></li>
     <li></li>
     <li></li>
     <li></li>
     <li></li>
   </ul>
   ```

1. Paste this CSS code into the Custom CSS input:

   ```css
   @import url('https://ccrsxx.github.io/violetkuma/public/style.css');
   ```

1. Click Save

## Development

Here are the steps to run the project locally.

1. Clone the repository

   ```bash
   git clone https://github.com/ccrsxx/violetkuma.git
   ```

1. Change directory to the project

   ```bash
   cd violetkuma
   ```

1. Install dependencies

   ```bash
   npm i
   ```

1. Run the project

   ```bash
   npm run dev
   ```

1. Same steps as the installation, except for the Custom CSS input, you need to use the local url instead.

   ```css
   @import url('http://localhost:3000/public/style.css');
   ```
