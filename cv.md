## Kamok Evgeniy

## Contacts
- **Location:** Minsk, Belarus
- **Phone:** +375 - 29 - 8888 - 720 
- **Email:** evgkamok@gmail.com
- **GitHub:** [evgkamok](https://github.com/evgkamok)

## About me
Highly motivated web developer, 34 years old, with a college degree in software development. Skilled in HTML, CSS, and JavaScript, with hands-on experience in small projects and exercises. Focused on creating functional web applications, solving problems efficiently, and improving skills in modern web technologies. Eager to gain professional experience and contribute to real-world projects.

## Skills
- Git
- HTML5
- CSS/SASS
- JavaScript (Basic)
- React JS, Redux (intermediate level knowledge).
-  Figma

## Code examples
```jsx
import { useEffect } from 'react'

export default function useClickOutside(element, cb) {
	useEffect(() => {
		const handleClickOutside = e => {
			if (element.current) {
				if (!element.current.contains(e.target)) {
					cb(e)
				}
			}
		}
		window.addEventListener('click', handleClickOutside)
		return () => {
			window.removeEventListener('click', handleClickOutside)
		}
	}, [element, cb])
}
```

## Education
- Tekhnologicheskiy kolledzh, UO "Grodnenskiy gosudarstvenny universitet im. Ya. Kupaly"
    - Программное обеспечение информационных технологий
- **Udemy**
    - [WEB-разработчик \| Udemy](https://www.udemy.com/course/webdeveloper/)
    - [Полный курс по JavaScript + React - с нуля до результата \| Udemy](https://www.udemy.com/course/javascript_full/?couponCode=MT250915G1)
    
## Languages
- **Russian** - native speaker.
- **English** - A2 (B1 in process…)
