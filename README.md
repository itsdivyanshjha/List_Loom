# ListLoom

ListLoom is a modern task management application designed to help you weave your way to productivity. With a sleek and intuitive interface, ListLoom allows users to manage tasks efficiently, ensuring that nothing falls through the cracks.

## Features

- **Responsive Design**: ListLoom is designed to work seamlessly across devices, ensuring a consistent experience whether you're on a desktop or mobile.
- **Task Management**: Easily create, update, and delete tasks. Mark tasks as complete or incomplete with a simple click.
- **Drag and Drop**: Reorder tasks effortlessly using the drag-and-drop feature powered by Sortable.js.
- **Animations**: Enjoy smooth animations for a delightful user experience, including slide-in, fade-in, and shimmer effects.
- **Customizable Themes**: Utilize CSS variables to easily adjust the color scheme and appearance of the application.

## Codebase Overview

### HTML Templates

- **`base/templates/base/main.html`**: The main HTML template that structures the application layout. It includes a sidebar for navigation and a main content area where task-related content is displayed. The template uses Django's templating language to dynamically render content.

### CSS Styling

- **Inline Styles**: The application uses inline CSS within the `main.html` file to define styles for various components, including animations, color schemes, and responsive design adjustments.
- **CSS Variables**: Defined in the `:root` selector for easy theme customization.

### JavaScript

- **Sortable.js**: Integrated for drag-and-drop functionality, allowing users to reorder tasks within the task list.

### Python (Django)

- **Django Framework**: ListLoom is built using Django, a high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **Template Inheritance**: Utilizes Django's template inheritance to extend base templates and inject dynamic content.

## Getting Started

To get started with ListLoom, follow these steps:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/yourusername/listloom.git
   cd listloom
   ```

2. **Set Up the Virtual Environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

5. **Access the Application**: Open your web browser and navigate to `http://127.0.0.1:8000` to start using ListLoom.

## Contributing

We welcome contributions to ListLoom! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

---

Thank you for choosing ListLoom to manage your tasks. We hope it helps you stay organized and productive!
