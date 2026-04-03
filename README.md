# CAT Daily Study Planner - Optima Learn

An AI-powered CAT exam preparation web application that generates personalized daily study plans using Google's Gemini AI.

## 🎯 Features

- **Personalized Study Plans**: AI-generated daily study schedules based on your proficiency levels
- **Progress Tracking**: Track your daily progress and maintain study streaks
- **Adaptive Learning**: Plans adapt based on your performance and feedback
- **Comprehensive Coverage**: Covers all CAT sections - QA, VARC, and DILR
- **Beautiful UI**: Modern, responsive design with smooth animations
- **Local Storage**: Saves your profile and progress locally

## 📚 Sections Covered

### Quantitative Aptitude (QA)
- Arithmetic, Algebra, Geometry, Number System
- Advanced problem-solving techniques
- Time-saving shortcuts and methods

### Verbal Ability & Reading Comprehension (VARC)
- Reading comprehension strategies
- Vocabulary enhancement
- Grammar and verbal reasoning

### Data Interpretation & Logical Reasoning (DILR)
- Data interpretation techniques
- Logical reasoning puzzles
- Case study analysis

## 🚀 Getting Started

### Prerequisites
- Google Gemini API key
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vanisharma04/CAT_Dailyplan.git
   cd CAT_Dailyplan
   ```

2. **Get Gemini API Key**
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create a new API key
   - Copy the key for use in the application

3. **Run the application**
   - Simply open `index (1).html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Then visit http://localhost:8000
     ```

## 📖 How to Use

### 1. Setup Your Profile
- Enter your Gemini API key
- Set your target CAT exam date
- Rate your proficiency in each section (1-5 scale)
- Select daily study hours available
- Choose your target percentile

### 2. Generate Study Plan
- Click "Generate My Study Plan"
- The AI will create a personalized daily schedule
- Review your plan with specific tasks and resources

### 3. Track Progress
- At the end of each day, mark your progress:
  - **Completed**: Finished all tasks
  - **Partial**: Completed some tasks
  - **Not Done**: Couldn't complete tasks

### 4. Get Next Day's Plan
- Submit your progress to generate tomorrow's plan
- The AI adapts based on your performance
- Maintain your study streak for motivation

## 🎨 Features in Detail

### Dashboard
- **Study Streak Counter**: Tracks consecutive days of study
- **Days Until CAT**: Countdown to your exam
- **Today's Focus**: Highlights your weakest area
- **Weekly Progress**: Shows overall completion percentage

### Study Plan Components
- **Topic-specific tasks**: Detailed actionable items
- **Time allocation**: Balanced distribution across sections
- **Resource recommendations**: Specific study materials
- **Motivational tips**: Daily encouragement

### Progress System
- **Visual progress cards**: Easy-to-use interface
- **Performance tracking**: Monitor improvement over time
- **Adaptive algorithms**: Plans evolve with your skills

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **AI Integration**: Google Gemini API
- **Storage**: LocalStorage for data persistence
- **Styling**: CSS Grid, Flexbox, Custom Properties
- **Icons**: Custom SVG graphics

## 📱 Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 🔧 Configuration

### API Setup
The application uses Google's Gemini API for generating study plans. Make sure to:
1. Enable the Gemini API in your Google Cloud project
2. Set up billing if required
3. Use a valid API key

### Customization
You can modify:
- Study plan templates in the prompt generation
- UI colors through CSS variables
- Section weightings and priorities

## 📊 Data Structure

### User Profile
```javascript
{
  examDate: "2024-11-24",
  dailyHours: 4,
  targetPercentile: 95,
  proficiency: {
    qa: 3,
    varc: 4,
    dilr: 2
  }
}
```

### Study Plan
```javascript
{
  date: "2024-05-15",
  totalHours: 4,
  sections: [
    {
      name: "QA",
      topic: "Percentage and Profit Loss",
      hours: 1.5,
      tasks: ["Solve 20 problems", "Review formulas"],
      resource: "Arun Sharma QA book"
    }
  ],
  motivationalTip: "Consistency is key to success!"
}
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Google Gemini AI for powering the study plan generation
- CAT aspirants community for feedback and suggestions
- Open source community for inspiration and tools

## 📞 Support

If you face any issues or have suggestions:
- Create an issue on GitHub
- Check the troubleshooting section below

### Common Issues

**Q: API key not working**
- Ensure the Gemini API is enabled in your Google Cloud project
- Check if the API key has sufficient permissions
- Verify billing is set up if required

**Q: Study plans not generating**
- Check your internet connection
- Verify API key is correctly entered
- Try refreshing the page and generating again

**Q: Progress not saving**
- Ensure browser allows local storage
- Check if browser is in private/incognito mode
- Try clearing browser cache

---

## 🌟 Star the Repository

If this project helped you in your CAT preparation, please give it a ⭐ on GitHub!

**Made with ❤️ for CAT aspirants**
