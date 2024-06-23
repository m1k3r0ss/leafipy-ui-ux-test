# UI/UX Testing Report Leapify

## Project Information
- **Project Name:** Leapify ([Website](https://musing-saha-2d39c9.netlify.app/))
- **Date:** 23 June, 2024
- **Version:** N/A
- **Reported by:** Sandhikshyan Roy

## Test Environment
- **Device Model:** iPhone 13 (MLPF3HN/A)
- **iOS Version:** iOS 17.5.1 (21F90)
- **Browser (if applicable):** Safari 17.5.1
- **Testing Tools:**
  - Figma

## Figma Design References
- **Figma Project Link:** [Figma Project](https://www.figma.com/design/dflaGXC6EfwEYhufOlxtHQ/LeapifyTalk?node-id=0-1)

## Summary
- **Total Issues Found:**
  - Usability Issues: 1
  - Visual Design Issues: 5

## Detailed Findings

### Visual Design Issues

#### 1. Card Elements Design Mismatch
- **Description:**
  - Icon mismatch in Cards, Padding between icons and text not consistent.
- **Figma Reference:** [Card Design](https://www.figma.com/design/dflaGXC6EfwEYhufOlxtHQ/LeapifyTalk?node-id=295-3)
- **Actual Website Reference:** [Website](https://musing-saha-2d39c9.netlify.app/)
- **Difference Observed:**
  - Icons switched between cards (“Chat, Video, Phone”) and “Personalized Match”.
  - No gap or padding between icons and text on any card.
- **Severity:** Low
- **Suggested Improvement:**
  - Change icon to what is on the Figma design although, the one on the app is more appropriate.

#### 2. Banner Height Mismatch
- **Description:**
  - Banner height is very short.
- **Figma Reference:** [Banner Design](https://www.figma.com/design/dflaGXC6EfwEYhufOlxtHQ/LeapifyTalk?node-id=298-10&t=sqtUxWWE6nlshPDG-4)
- **Actual Website Reference:** [Website](https://musing-saha-2d39c9.netlify.app/)
- **Difference Observed:**
  - Banner height on the app is very short compared to the design reference on Figma.
- **Severity:** Low
- **Suggested Improvement:**
  - Change height to be consistent with aspect ratio on Figma reference.

#### 3. Payment Card CSS Styling Inconsistent
- **Description:**
  - Payment Card and pagination elements to navigate through the different cards have no gap and cuts off into the card’s shadow (CSS).
- **Figma Reference:** [Payment Card Design](https://www.figma.com/design/dflaGXC6EfwEYhufOlxtHQ/LeapifyTalk?node-id=312-48&t=sqtUxWWE6nlshPDG-4)
- **Actual Website Reference:** [Website](https://musing-saha-2d39c9.netlify.app/)
- **Difference Observed:**
  - Shadow of Card maintained on Figma design not consistent with App.
- **Severity:** Medium
- **Suggested Improvement:**
  - Fix CSS styling to maintain shadow and gap between Card and Pagination elements below.

#### 4. Customer Review Cards Don’t Show Complete Text
- **Description:**
  - Customer Review Cards missing pictures and show text that is cut off.
- **Figma Reference:** [Customer Review Cards](https://www.figma.com/design/dflaGXC6EfwEYhufOlxtHQ/LeapifyTalk?node-id=295-3&t=sqtUxWWE6nlshPDG-4)
- **Actual Website Reference:** [Website](https://musing-saha-2d39c9.netlify.app/)
- **Difference Observed:**
  - Text complete on Figma design, not on iOS App.
- **Severity:** Severe
- **Suggested Improvement:**
  - Fix text size or text-margin to show the complete text.

#### 5. FAQ Expand Icons Different
- **Description:**
  - FAQ answer expand icons are not consistent.
- **Figma Reference:** [FAQ Design](https://www.figma.com/design/dflaGXC6EfwEYhufOlxtHQ/LeapifyTalk?node-id=295-3&t=sqtUxWWE6nlshPDG-4)
- **Actual Website Reference:** [Website](https://musing-saha-2d39c9.netlify.app/)
- **Difference Observed:**
  - Figma reference uses the plus sign(+) icon while the iOS App uses a down arrow.
- **Severity:** Low
- **Suggested Improvement:**
  - Change the icon to “+”.

### Usability Issues

#### 1. Pricing Card Navigation
- **Description:**
  - When the end user switches between the different pricing cards, the last card “Enterprise” moves down and breaks the UI for a second before returning to its normal expected position. When moving left, the same thing happens but with the “Commercial” card.
- **Steps to Reproduce:**
  1. Navigate left or right using the Navigation arrows.
- **Impact on User:**
  - Breaks the UI for a second and looks bad.
- **Severity:** Minor
- **Suggested Improvement:**
  - Fix the navigation issue.
- **Figma Reference:** [Pricing Card Navigation](https://www.figma.com/design/dflaGXC6EfwEYhufOlxtHQ/LeapifyTalk?node-id=312-48&t=sqtUxWWE6nlshPDG-4)

## Summary and Recommendations

### Overall Summary
- Overall there are some minor issues with the text formatting and icon-sizing in the cards on the home page and other minor issues in animation and navigation.

### Key Recommendations
- Prioritize fixing the Pricing card Navigation before other issues.

## Report Submission
- **Date Submitted:** 23 June, 2024
- **Submitted by:** Sandhikshyan Roy
- **Contact Information:** sandhikshyanroy@gmail.com
