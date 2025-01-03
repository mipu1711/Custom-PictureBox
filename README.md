# Custom PictureBox Control

A versatile and feature-rich PictureBox control for your .NET applications, enabling advanced image interactions and drawing capabilities.

## Features

- **Zoom & Pan:** Easily navigate through images with smooth zooming and panning functionality.
- **Draw Straight Lines:** Create precise straight lines on your images.
- **Draw Rectangles:** Add rectangular shapes with customizable properties.
- **Draw Curves:** Implement freehand and curved drawings for more dynamic illustrations.
- **Rulers:** Utilize built-in rulers for accurate measurements and alignment.

## Installation
**Add to Your Project:**
   - Include the `CustomPictureBox.cs` file in your project.
   - Ensure all dependencies are referenced correctly.

## Usage

### Initializing the Control

```csharp
using CustomPictureBoxNamespace;

public partial class MainForm : Form
{
    private CustomPictureBox customPictureBox;

    public MainForm()
    {
        InitializeComponent();
        customPictureBox = new CustomPictureBox
        {
            Dock = DockStyle.Fill
        };
        this.Controls.Add(customPictureBox);
    }
}
```

### Zoom & Pan

- **Zoom In/Out:**
  Use the mouse wheel or dedicated buttons to zoom into or out of the image.
  
- **Pan:**
  Click and drag the image to navigate different sections when zoomed in.

### Drawing Tools

- **Straight Lines:**
  Select the line tool from the toolbar and click two points on the image to draw a straight line.

- **Rectangles:**
  Choose the rectangle tool, then click and drag to create a rectangle of desired size.

- **Curves:**
  Select the curve tool and click multiple points to create smooth, freehand curves.

### Rulers

- **Display Rulers:**
  Toggle rulers on the top and left edges of the PictureBox for precise measurements.
  
- **Measurement Units:**
  Configure measurement units (pixels, inches, centimeters) based on your requirements.

## Customization

You can customize the appearance and behavior of the Custom PictureBox by modifying the properties in the `CustomPictureBox.cs` file. Adjust colors, line widths, and other settings to fit the aesthetic of your application.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).

## Resources

- [.NET Documentation](https://docs.microsoft.com/en-us/dotnet/)
- [WinForms Controls](https://docs.microsoft.com/en-us/dotnet/desktop/winforms/controls/overview-of-windows-forms-controls)

---

Feel free to reach out if you have any questions or need further assistance!
