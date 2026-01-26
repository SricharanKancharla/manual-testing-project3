# Online Learning Platform Manual Testing Project

![Testing](https://img.shields.io/badge/Testing-Manual-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-Web-orange)
![Focus](https://img.shields.io/badge/Focus-Course_Discovery-purple)

## 📋 Project Overview

This project demonstrates comprehensive manual testing of an online learning platform (similar to Udemy/Coursera), focusing on course browsing, filtering, enrollment, and wishlist management. The testing validates the complete user journey from course discovery through enrollment to ensure an intuitive and seamless learning experience.

## 🎯 Objectives

- Validate course catalog browsing and navigation
- Ensure accurate filtering and search functionality
- Verify course details page information display
- Test free course enrollment workflow
- Validate wishlist management features
- Ensure UI/UX consistency and responsiveness
- Test pagination and result navigation

## 🔍 Testing Scope

### In Scope
- Course Browsing (Catalog display and navigation)
- Course Filtering (Category, price, difficulty, rating)
- Course Search (Keyword search and results)
- Course Details (Information, curriculum, reviews)
- Course Enrollment (Free course enrollment process)
- Wishlist Management (Add/remove courses)
- Pagination (Course list navigation)
- UI/UX Validation

### Out of Scope
- Paid course enrollment and payment processing
- Course content viewing and video playback
- User registration and profile management
- Course creation and instructor dashboard
- Assessments, quizzes, and assignments
- Certificates and course completion tracking
- Discussion forums and Q&A sections
- Email notifications
- Mobile application testing

## 🧪 Test Scenarios

| Scenario ID | Description | Priority |
|------------|-------------|----------|
| TS_01 | Browse courses in the catalog | High |
| TS_02 | Filter courses by category, price, difficulty, rating | High |
| TS_03 | View detailed course information | High |
| TS_04 | Enroll in a free course | High |
| TS_05 | Add and remove courses from wishlist | High |

## 📝 Test Cases (9 Total)

| TC ID | Scenario | Test Case Description | Expected Result |
|-------|----------|----------------------|-----------------|
| TC_01 | TS_01 | View course list on homepage | Course list displayed with thumbnails |
| TC_02 | TS_02 | Apply category filter to courses | Results updated based on filter |
| TC_03 | TS_03 | Open a course to view details | Course details page opens |
| TC_04 | TS_04 | Enroll in a free course | User successfully enrolled |
| TC_05 | TS_05 | Add a course to wishlist | Course added to wishlist |
| TC_06 | TS_05 | Remove a course from wishlist | Course removed successfully |
| TC_07 | TS_04 | Attempt enrollment without login | Login prompt shown |
| TC_08 | TS_02 | Search for a specific course | Relevant search results displayed |
| TC_09 | TS_03 | Navigate through course pagination | Pagination works correctly |

## 🛠️ Test Environment

**Primary Browser:** Google Chrome (Latest Version)

**Operating System:** Windows 10

**Additional Testing:**
- Mozilla Firefox (Latest Version)
- Microsoft Edge (Latest Version)

**Test Data:**
- Sample courses across various categories (Technology, Business, Arts, Health)
- Courses with different price points (Free, Paid)
- Courses with varying difficulty levels (Beginner, Intermediate, Advanced)
- Courses with different ratings and review counts
- Search keywords (course names, topics, instructors)

## 📊 Testing Approach

### Test Design Techniques
- **Equivalence Class Partitioning** - Course categories, price ranges, difficulty levels
- **Boundary Value Analysis** - Pagination limits, filter boundaries, search character limits
- **Decision Table Testing** - Filter combinations and result impacts
- **Use Case Testing** - Real-world course discovery scenarios
- **Error Guessing** - Edge cases (empty results, no courses in category)
- **Exploratory Testing** - Ad-hoc testing for unexpected issues

### Testing Types Performed
- **Functional Testing** - Feature functionality verification
- **UI Testing** - Interface elements and layout validation
- **Usability Testing** - Course discovery ease and filter intuitiveness
- **Search Testing** - Search relevance and result accuracy
- **Filter Testing** - Filter combinations and result updates
- **Regression Testing** - Existing functionality integrity

## 📁 Project Structure

```
online-learning-platform-testing/
│
├── Test_Plan/
│   └── Test_Plan_OnlineLearning_Manual_Testing.docx
│
├── Test_Artifacts/
│   └── Test_Artifacts.xlsx
│
├── Test_Cases/
│   └── Test_Cases_OnlineLearning.xlsx
│
├── Test_Execution/
│   └── Test_Execution_Report.xlsx
│
├── Defect_Reports/
│   └── Defect_Log.xlsx
│
├── Screenshots/
│   ├── Course_Browsing/
│   ├── Filters/
│   ├── Search/
│   ├── Enrollment/
│   ├── Wishlist/
│   └── Defects/
│
└── README.md
```

## 📝 Test Deliverables

1. **Test Plan Document** - Comprehensive testing strategy for course discovery
2. **Test Scenarios** - 5 high-level test scenarios
3. **Test Cases** - 9 detailed test cases with execution steps
4. **Test Execution Report** - Execution status with pass/fail results
5. **Defect Report** - Detailed defect log with severity and priority
6. **Test Summary Report** - Final metrics and analysis
7. **Screenshots** - Visual evidence of test execution and defects

## 🔧 Tools Used

| Tool | Purpose |
|------|---------|
| Google Chrome | Primary browser for test execution |
| Mozilla Firefox / MS Edge | Cross-browser compatibility testing |
| Microsoft Excel | Test case management and defect tracking |
| Windows Snipping Tool | Screenshot capture for documentation |
| Microsoft Word | Test plan and report documentation |

## 👥 Team Structure

- **Test Lead:** TL_ID_01 - Overall test planning, coordination, and reporting
- **Tester 1:** Course browsing and pagination testing
- **Tester 2:** Filtering and search functionality testing
- **Tester 3:** Enrollment and wishlist testing

## ⚠️ Risks and Mitigations

| Risk | Mitigation Strategy |
|------|---------------------|
| Limited testing timeframe | Focus on critical browsing and enrollment flows; prioritize high-impact test cases |
| Insufficient course catalog test data | Work with sample courses; document data limitations; request additional test courses |
| Inconsistent filter results | Document all filter combinations tested; verify with multiple data sets |
| Platform performance issues | Test during off-peak hours; document performance observations separately |
| Incomplete course information | Use available courses; focus on functionality over content completeness |

## 📅 Test Schedule

| Activity | Timeline |
|----------|----------|
| Test Plan Creation | January 25, 2026 |
| Test Scenario & Case Creation | January 25, 2026 |
| Test Execution & Defect Logging | January 26, 2026 |
| Test Summary Report | January 26, 2026 |

## 🎓 Key Focus Areas

### Course Discovery
- Course catalog display and layout
- Course thumbnail and information presentation
- Category-based browsing
- Course cards and metadata

### Filtering & Search
- Multi-criteria filtering (category, price, difficulty, rating)
- Filter combinations and interactions
- Search keyword relevance
- Search result accuracy and ranking
- Filter reset and clearing

### Enrollment Process
- Free course enrollment workflow
- Login requirement validation
- Enrollment confirmation
- Access control for unauthenticated users

### Wishlist Management
- Add course to wishlist functionality
- Remove course from wishlist
- Wishlist persistence across sessions
- Wishlist icon state management

### Navigation & Pagination
- Page navigation controls
- Items per page display
- Current page indication
- First/last page handling

## 📈 Test Metrics

*(To be updated after test execution)*

- **Total Test Cases:** 9
- **Test Cases Executed:** TBD
- **Pass Rate:** TBD%
- **Defects Found:** TBD
- **Critical/High Severity Defects:** TBD
- **Test Coverage:** 100% (Course Discovery & Enrollment Module)

## 🔗 Test Execution Summary

### Entry Criteria
- Test cases reviewed and approved
- Online learning platform accessible
- Course catalog populated with test data
- Test environment set up

### Exit Criteria
- All 9 test cases executed
- Defects logged with evidence
- Critical browsing and enrollment functionalities verified
- Test reports completed

## 💡 Assumptions

- Online learning platform is publicly accessible and stable
- Course catalog is populated with diverse courses across categories
- Free courses are available for enrollment testing
- User authentication system is functional for login-required features
- Filters and search functionality are implemented and active
- Internet connectivity remains stable during testing

## 📄 Documentation Standards

All test artifacts follow industry-standard formats:
- **Test Cases:** TC ID, Description, Preconditions, Steps, Expected Results, Actual Results, Status
- **Defects:** Defect ID, Title, Module, Severity, Priority, Steps to Reproduce, Expected vs Actual, Screenshots, Environment

## 🚀 How to Use This Repository

1. Review the **Test Plan** document for complete testing strategy
2. Examine **Test Scenarios** for high-level coverage
3. Study **Test Cases** for detailed test steps
4. Check **Test Execution Report** for results
5. Review **Defect Reports** for identified issues
6. View **Screenshots** for visual evidence

## 🎯 Test Case Highlights

### Course Browsing & Navigation
- **TC_01:** Course list display validation
- **TC_09:** Pagination functionality

### Filtering & Search
- **TC_02:** Filter application and result updates
- **TC_08:** Course search functionality

### Enrollment & Access Control
- **TC_04:** Free course enrollment
- **TC_07:** Login requirement validation

### Wishlist Management
- **TC_05:** Add course to wishlist
- **TC_06:** Remove course from wishlist

### Course Details
- **TC_03:** Course information page display

## 🔍 Testing Highlights

### Positive Test Cases
- Course list displays correctly with all information
- Filters update results accurately
- Search returns relevant courses
- Free course enrollment completes successfully
- Wishlist add/remove operations work correctly
- Pagination navigates between pages properly

### Negative Test Cases
- Enrollment without login triggers authentication prompt
- Empty search returns appropriate message
- Invalid filter combinations handled gracefully
- Edge cases for pagination boundaries

## 🎓 Key Learnings

- Importance of comprehensive filter combination testing
- Critical role of search relevance in user experience
- Need for clear enrollment flow indicators
- Value of wishlist persistence across sessions
- Significance of proper pagination implementation
- Impact of course information completeness on user decisions

## 📧 Contact

For any questions or clarifications about this testing project, please feel free to reach out.

---

## 🙏 Acknowledgments

This project was created as a demonstration of manual testing skills with focus on e-learning platform functionality, course discovery workflows, and enrollment processes.

---

**Note:** This is a personal portfolio project created to showcase manual testing expertise in online learning platforms. All names, teams, and scenarios are for demonstration purposes.

---

## 📊 Project Status

**Current Status:** Testing Completed

**Next Steps:**
- [ ] Complete test execution report
- [ ] Generate final test summary

---

## 🏆 Skills Demonstrated

- Manual Testing (E-Learning Platforms)
- Test Planning & Strategy
- Test Case Design & Documentation
- Defect Reporting & Tracking
- Filter & Search Testing
- Enrollment Flow Testing
- Wishlist Functionality Testing
- Pagination Testing
- UI/UX Testing
- Cross-Browser Testing
- Usability Testing
- Exploratory Testing

---

## 📚 Platform Features Tested

### Core Functionality
- Course catalog browsing
- Advanced filtering system
- Course search capability
- Course details display
- Free course enrollment
- Wishlist management
- Pagination controls

### User Experience Elements
- Course card design and information
- Filter UI and interactions
- Search bar and results display
- Enrollment button states
- Wishlist icon toggle
- Page navigation controls
- Responsive layout

---

*Last Updated: January 26, 2026*
