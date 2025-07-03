# Table-Based Layout (Pre-CSS Era - 1990s)

This implementation demonstrates how websites were built before CSS became widely adopted, using HTML tables for page layout.

## Demo
Open `index.html` in your browser to see this layout approach in action.

## Key Techniques Used

### Layout Structure
- **Master Table**: The entire page is wrapped in a single `<table>` element
- **Three-Column Layout**: Created using `<td>` elements with percentage-based widths:
  - Left sidebar: 20% width
  - Main content: 60% width  
  - Right sidebar: 20% width

### Visual Styling (HTML Attributes)
- `bgcolor="#808080"` - Sets background color on the body
- `width="100%"` - Makes table span full width
- `border="0"` - Removes table borders
- `cellspacing="0"` and `cellpadding="10"` - Controls spacing
- `valign="top"` - Aligns content to top of cells
- `<font>` tags - Controls typography and sizing

### Deprecated Practices Used
This implementation intentionally uses deprecated HTML features to authentically represent 1990s web development:
- Inline styling with HTML attributes
- `<font>` tags for typography
- Tables for layout instead of data
- Presentational HTML instead of semantic markup

## Pros of This Approach (in the 1990s)
- ✅ Reliable cross-browser layout
- ✅ No CSS knowledge required
- ✅ Consistent grid system
- ✅ Widely supported

## Cons of This Approach
- ❌ Not semantically correct
- ❌ Poor accessibility
- ❌ Difficult to maintain
- ❌ Not responsive
- ❌ Larger file sizes
- ❌ Mixing content with presentation

## Historical Context
Before CSS, web developers had limited options for creating complex layouts. Tables provided a workaround that allowed for multi-column designs and consistent positioning, even though they weren't intended for this purpose.
