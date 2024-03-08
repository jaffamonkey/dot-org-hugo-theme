---
title: Accessbility automation
description: Make Accessibility an integral to your project pipeline
---

> With a simple set of choices, we can run accessibility tests in our pipelines and generate useful feedback for your development design teams.

While manual checks are always recommended, you can achieve a high degree of prevention by introducing automation into your design and development cycles.

### Web
- Windows/MacOS
	- All content
	  Content by template
		- Sitemap or Urls list
		(_Level AA only_)
			- Screenreader Automation
			(_Level AA only_)
				- Voiceover
				(_Level AA only_)
				- NVDA
				(_Level AA only_)
		- Supply user guide
			- Manual testing
				- Voiceover
				(_Level AA only_)
				- NVDA
				(_Level AA only_)
				- Design & UX
			- UX Testing +
			(_Level AA only_)
				- Disabilities & UX
				(_Level AA only_) **
			- Manual screenreader checks
			(_Level AA only_)
				- Voiceover
				(_Level AA only_)
				- NVDA
				(_Level AA only_)
		- Login Required?
			- Supply Login URL
				- Extract login script
	- DevOps
		- Run SonarQube
		(_Level AA only_)
		- Sitemap or Urls list
			- Pa11y CI
			- AxeScan
			- Pa11y Dashboard
		- Build Server
			- SonarQube Plugin
			(_Level AA only_)
			- a11y plugins

### Mobile Web
- Android/iOS
	- All content  
	  Content by template
		- Sitemap or Urls list
			- Screenreader Automation
			(_Level AA only_)
				- Voiceover
				(_Level AA only_)
				- NVDA
				(_Level AA only_)
		- Supply user guide
			- Manual testing
				- Voiceover
				(_Level AA only_)
				- TalkBack
				(_Level AA only_)
				- Design & UX
			- UX Testing +
			(_Level AA only_)
				- Disabilities & UX
				(_Level AA only_) **    
			- Manual screenreader checks
			(_Level AA only_)
				- Voiceover
				(_Level AA only_)
				- TalkBack
				(_Level AA only_)
		- Login Required?
			- Supply Login URL
				- Extract login script
	- DevOps
		- Run SonarQube
		(_Level AA only_)
		- Sitemap or Urls list
			- Pa11y CI
			- AxeScan
				- 
			- Pa11y Dashboard
		- Build Server
			- SonarQube Plugin
			(_Level AA only_)
			- a11y plugins

### Mobile App
- Android/iOS
	- All content  
	  Content by template
		- Supply user guide
			- Manual testing
				- Voiceover
				(_Level AA only_)
				- TalkBack
				(_Level AA only_)
				- Design & UX
			- UX Testing
			(_Level AA only_)
				- Disabilities & UX
				(_Level AA only_) ** 
		- Login Required?
			- Supply Login details
	- DevOps
		- Run SonarQube
		(_Level AA only_)
		- Build Server
			- SonarQube Plugin
			(_Level AA only_)
	- Mobile tools check
		- Android
		- iOS



** _Disabilities: Dyslexia, Age, Language, Culture, Education, Economic position, Tech aptitude, Cognitive, Physical Mobility, Auditory._