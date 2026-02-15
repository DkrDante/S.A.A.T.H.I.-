# S.A.A.T.H.I - Smart Adaptive AI Tutor for Holistic Intelligence

**Built on Nomi V2: The Living Companion**

S.A.A.T.H.I is an emotionally intelligent, privacy-focused AI tutor designed to run locally on Apple Silicon hardware. Unlike standard educational assistants, S.A.A.T.H.I combines deep emotional intelligence with adaptive learning capabilities, creating a holistic educational experience that nurtures both cognitive and emotional growth.

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://travis-ci.org/yourusername/nomi-v3) [![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](https://github.com/yourusername/nomi-v3/releases)

## 🎓 What is S.A.A.T.H.I?

S.A.A.T.H.I (Smart Adaptive AI Tutor for Holistic Intelligence) represents the evolution of AI-assisted learning. It's not just a tutoring system—it's a companion that understands your learning style, emotional state, and educational needs, adapting in real-time to provide personalized guidance.

### Core Philosophy

- **Holistic Intelligence**: Nurtures cognitive, emotional, and social development
- **Adaptive Learning**: Adjusts teaching methods based on individual learning patterns
- **Emotional Awareness**: Recognizes and responds to learner's emotional state
- **Privacy-First**: All processing happens locally—your learning journey stays private

## ✨ Key Features

### Educational Capabilities

- **Adaptive Tutoring**: Personalized learning paths based on performance and comprehension
- **Multi-Subject Support**: Mathematics, Science, Languages, and more
- **Real-Time Assessment**: Continuous evaluation of understanding and progress
- **Interactive Learning**: Conversational teaching with visual and audio feedback
- **Homework Assistance**: Guided problem-solving without giving direct answers

### Emotional Intelligence

- **Mood-Aware Teaching**: Adjusts teaching style based on learner's emotional state
- **Encouragement System**: Provides motivation and positive reinforcement
- **Frustration Detection**: Recognizes when learner is struggling and adapts approach
- **Celebration of Progress**: Acknowledges achievements and milestones

### Technical Features

- **100% Local & Private**: All processing (STT, LLM, TTS) happens on-device
- **Vision-Enabled**: Uses camera to detect engagement and emotional state
- **Voice Interaction**: Natural conversation-based learning
- **Persistent Memory**: Remembers learning history, preferences, and progress
- **Web-Aware**: Fetches real-time information for current topics and research

### Memory & Personalization

- **Learning Profile**: Tracks strengths, weaknesses, and learning style
- **Progress Tracking**: Maintains detailed history of topics covered and mastery levels
- **Relationship Building**: Develops understanding of learner's interests and goals
- **Contextual Recall**: References previous lessons and builds on prior knowledge

## 🎯 Use Cases

### For Students

- **Homework Help**: Get guided assistance without direct answers
- **Concept Clarification**: Ask questions and receive personalized explanations
- **Exam Preparation**: Practice problems with adaptive difficulty
- **Learning Companion**: Build confidence through supportive interaction

### For Self-Learners

- **Skill Development**: Learn new subjects at your own pace
- **Knowledge Retention**: Benefit from spaced repetition and review
- **Curiosity Exploration**: Dive deep into topics of interest
- **Progress Tracking**: Monitor your learning journey

### For Educators

- **Supplementary Tool**: Provide students with additional support
- **Personalized Learning**: Address individual student needs
- **Progress Monitoring**: Track student engagement and understanding
- **Resource Efficiency**: Scale personalized attention

## 🛡️ Privacy & Security

### Data Privacy

- **Strictly Local**: All processing happens on your device
- **No Cloud Dependency**: No data transmitted to external servers
- **Encrypted Storage**: Local data stored securely
- **User Control**: Full control over data retention and deletion

### What Gets Stored

- Conversation logs (local text files)
- Learning progress and profiles
- Face recognition data (if registered)
- Session history and analytics

### What Never Leaves Your Device

- Voice recordings
- Video/camera feed
- Personal information
- Learning content and conversations

## 🔧 Configuration

### Persona Customization

Edit the `PERSONA` variable in `main.py` to customize teaching style and personality.

### Vision Settings

Adjust vision system parameters in `modules/tracking.py`:

- Face detection sensitivity
- Emotion recognition thresholds
- Object detection preferences

### Memory Settings

Configure memory behavior in `modules/memory.py`:

- Retention policies
- Consolidation frequency
- Context window size

## 📊 Learning Analytics

S.A.A.T.H.I tracks:

- Session duration and frequency
- Topics covered and mastery levels
- Emotional engagement patterns
- Learning velocity and retention
- Areas requiring additional support

Access analytics through the memory system or logs directory.

## 🤝 Contributing

We welcome contributions! Areas of interest:

- Additional subject matter modules
- Enhanced assessment algorithms
- Improved emotion recognition
- Multi-language support
- Accessibility features

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 🗺️ Roadmap

### Phase 1 (Current)

- ✅ Core tutoring functionality
- ✅ Emotion-aware interaction
- ✅ Vision-based engagement tracking
- ✅ Multi-user support

### Phase 2 (Planned)

- 📝 Structured curriculum support
- 📝 Assessment and quiz generation
- 📝 Progress dashboards
- 📝 Parent/teacher reporting

### Phase 3 (Future)

- 🔮 Multi-modal learning (visual aids, diagrams)
- 🔮 Collaborative learning sessions
- 🔮 Integration with educational platforms
- 🔮 Advanced analytics and insights

## ❓ FAQ

**Q: How is S.A.A.T.H.I different from ChatGPT or other AI tutors?**  
A: S.A.A.T.H.I runs entirely locally, maintains persistent memory of your learning journey, adapts to your emotional state, and provides a consistent, personalized tutoring relationship.

**Q: Is my learning data safe?**  
A: Yes, all processing is local. No data leaves your device.

**Q: Can multiple students use the same system?**  
A: Yes, S.A.A.T.H.I supports multiple learner profiles with face recognition.

**Q: What subjects can S.A.A.T.H.I help with?**  
A: Currently supports general subjects. Specialized modules can be added.

**Q: Does it work offline?**  
A: Yes, core functionality works offline. Web search requires internet for real-time information.

**Q: Can I customize the teaching style?**  
A: Yes, the persona and teaching approach can be customized in the configuration.

## 📜 License

[MIT License] - Build, modify, and enhance your AI tutor.

## 🙏 Acknowledgments

Built on the foundation of Nomi V2, combining emotional intelligence with educational excellence.

---

**S.A.A.T.H.I**: Where technology meets empathy in education.
