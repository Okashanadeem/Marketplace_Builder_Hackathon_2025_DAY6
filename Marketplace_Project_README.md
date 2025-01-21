
# Marketplace Project (Marketplace_Builder_Hackathon_2025)

## Project Overview

The **Marketplace Project** is an e-commerce platform designed to display and sell various products. It offers a user-friendly interface with features like product listing, search functionality, and cart management. The project utilizes **Next.js**, **Sanity CMS** for content management, and **ShadCN** for UI components. It is deployed on **Vercel** for a seamless experience. The goal is to create a robust, responsive, and dynamic marketplace platform.

## Deployment

### Staging URL
- **[Staging Environment](https://marketplace-builder-hackathon-2025-proje-okashanadeems-projects.vercel.app/)**

### Deployment Steps
1. **Vercel Setup:**
   - Connected the GitHub repository to Vercel.
   - Deployed using **Next.js** with default build and deployment settings.

2. **Environment Variables:**
   - Configured environment variables in `.env.local` and Vercel for secure API access.
   - Key variables:
     - `NEXT_PUBLIC_SANITY_PROJECT_ID`: Sanity project ID
     - `NEXT_PUBLIC_SANITY_DATASET`: Sanity dataset (e.g., `production`)
     - `SANITY_API_KEY`: Sanity API key

## Features
- **Product Listing:** Displays products fetched from Sanity CMS.
- **Search Functionality:** Allows users to search for products by name or category.
- **Cart Operations:** Users can add, modify quantities, and remove items from the cart.
- **ShadCN Components:** Utilizes pre-built responsive UI components like buttons, input fields, and labels for a polished user experience.

## How to Test or Use the Project

### 1. **Access the Live Demo**
You can view the live version of the marketplace in both the staging and production environments:
- **[Staging Environment](https://marketplace-builder-hackathon-2025-proje-okashanadeems-projects.vercel.app/)**

### 2. **Testing the Application Locally**

#### Prerequisites
- **Node.js** (version 14 or higher)
- **npm** (Node Package Manager)

#### Steps to Test Locally:
1. **Clone the Repository:**
   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Okashanadeem/Marketplace_Builder_Hackathon_2025-project-deploy.git
   cd marketplace-project
   ```

2. **Install Dependencies:**
   Install the required dependencies using npm:
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env.local` file and add the necessary environment variables:
   ```bash
   NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
   NEXT_PUBLIC_SANITY_DATASET=production
   SANITY_API_KEY=your_sanity_api_key
   ```

4. **Run the Application:**
   Start the development server:
   ```bash
   npm run dev
   ```

5. **Access the Application:**
   Open your browser and go to `http://localhost:3000` to view the application.

## Tech Stack
- **Frontend:** Next.js, React, ShadCN
- **Backend/Content Management:** Sanity CMS
- **Deployment:** Vercel
- **Styling:** Tailwind CSS

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

For further questions or support, feel free to reach out to the project maintainer:  
[Okashanadeem](https://github.com/Okashanadeem)
