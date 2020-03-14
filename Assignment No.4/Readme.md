# Displaying Graphics in Applet
**java.awt.Graphics** class provides many methods for graphics programming.

### Commonly used methods of Graphics class:
1. public abstract void drawString(String str, int x, int y): is used to draw the specified string.
1. public void drawRect(int x, int y, int width, int height): draws a rectangle with the specified width and height.
1. public abstract void fillRect(int x, int y, int width, int height): is used to fill rectangle with the default color and specified width and height.
1. public abstract void drawOval(int x, int y, int width, int height): is used to draw oval with the specified width and height.
1. public abstract void fillOval(int x, int y, int width, int height): is used to fill oval with the default color and specified width and height.
1. public abstract void drawLine(int x1, int y1, int x2, int y2): is used to draw line between the points(x1, y1) and (x2, y2).
1. public abstract boolean drawImage(Image img, int x, int y, ImageObserver observer): is used draw the specified image.
1. public abstract void drawArc(int x, int y, int width, int height, int startAngle, int arcAngle): is used draw a circular or elliptical arc.
1. public abstract void fillArc(int x, int y, int width, int height, int startAngle, int arcAngle): is used to fill a circular or elliptical arc.
1. public abstract void setColor(Color c): is used to set the graphics current color to the specified color.
1. public abstract void setFont(Font font): is used to set the graphics current font to the specified font.
