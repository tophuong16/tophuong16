```javascript
import SoftwareDeveloper from 'hanoi';
import { Languages, Frameworks, Cms } from 'phuong/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Nguyen Thi To Phuong';
  title    = 'Senior Software Developer';
  location = 'Ha Noi, Viet Nam';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'TypeScript', 'PHP', 'Python', ...Languages];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL'];
  frameworks = ['Vue', 'React', 'Next.js', 'Laravel', 'React Native', ...Frameworks];
  cms        = ['Wordpress', 'Magento', 'Opencart', ...Cms];
}

```
