[![Spread OML](https://img.shields.io/badge/Spread-Open_Model_License-red)](https://github.com/fakerybakery/OpenModelLicense)

# Open Model License

A permissive license for distributing AI models. **Disclaimer: IANAL**

## The Problem

Existing licenses refer to "software" or "source code." Does an AI model count as "source code?"

## The Solution

Just modify the MIT license to clarify this!

## The Licenses

We propse four licenses.

To apply these licenses on Hugging Face:

```yaml
---
license: other
license_name: omlv1.1
license_link: https://github.com/fakerybakery/OpenModelLicense
---
```

### OMLv1.1 - Basic, permissive, MIT-like license

```
Open Model License 1.1 (OMLv1.1)
https://github.com/fakerybakery/OpenModelLicense

Copyright <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy of this model and associated documentation files (the "Model"), to deal in the Model without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Model, and to permit persons to whom the Model is furnished to do so, subject to the following conditions:

* The above copyright notice and this permission notice shall be included in all copies of the model in all formats, including quantized models and models in different formats from the original.
* Finetuned models may be licensed under different licenses and do not need to include the above copyright notice and this permission notice.

THE MODEL IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE MODEL OR THE USE OR OTHER DEALINGS IN THE MODEL.
```

**Update from OMLv1:** Add specific clause about finetuned models.

### ZOMLv1 - Almost no restrictions

```
"Zero" Open Model License 1.0 (ZOMLv1)
https://github.com/fakerybakery/OpenModelLicense

Copyright <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy of this model and associated documentation files (the "Model"), to deal in the Model without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, and/or sell copies of the Model, and to permit persons to whom the Model is furnished to do so, subject to the following conditions:

* The names of the authors and/or contributors may not be used to endorse any derivatives of this software without prior written permission from the copyright holders.

THE MODEL IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE MODEL OR THE USE OR OTHER DEALINGS IN THE MODEL.
```

### SOMLv1 - Basic, copyleft, MIT-based license with a focus on sharing

```
Sharing Open Model License 1.0 (SOMLv1)
https://github.com/fakerybakery/OpenModelLicense

Copyright <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy of this model and associated documentation files (the "Model"), to deal in the Model without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, and/or sell copies of the Model, and to permit persons to whom the Model is furnished to do so, subject to the following conditions:

* The above copyright notice and this permission notice shall be included in all copies of the model in all formats, including quantized models and models in different formats from the original.
* The above copyright notice and this permission notice shall be included in all derivatives of the model, including finetuned models.
* All derivatives of the model, including finetuned models, shall be licensed under the same SOMLv1 license or any later version of the SOML license as released by the Open Model License initiative (https://github.com/fakerybakery/OpenModelLicense).
* The names of the authors and/or contributors may not be used to endorse any derivatives of this software without prior written permission from the copyright holders.

THE MODEL IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE MODEL OR THE USE OR OTHER DEALINGS IN THE MODEL.
```

### NCOMLv1 - Non-commercial model license (this isn't an open-source model)

```
Non-Commercial Open Model License 1.0 (NCOMLv1)
https://github.com/fakerybakery/OpenModelLicense

Copyright <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy of this model and associated documentation files (the "Model"), to deal in the Model without restriction, including without limitation the rights to use, copy, modify, merge, publish, and/or distribute the Model, and to permit persons to whom the Model is furnished to do so, subject to the following conditions:

* The above copyright notice and this permission notice shall be included in all copies of the model in all formats, including quantized models and models in different formats from the original.
* The above copyright notice and this permission notice shall be included in all derivatives of the model, including finetuned models.
* All derivatives of the model, including finetuned models, shall be licensed under the same SOMLv1 license or any later version of the SOML license as released by the Open Model License initiative (https://github.com/fakerybakery/OpenModelLicense).
* This model and all derivatives may not be used for any commercial purposes, including but not limited to services accepting tips, donations, subscriptions, and advertisements.
* All software that uses, inferences, or links to this model shall be used for non-commercial purposes only.
* The names of the authors and/or contributors may not be used to endorse any derivatives of this software without prior written permission from the copyright holders.


THE MODEL IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE MODEL OR THE USE OR OTHER DEALINGS IN THE MODEL.
```
## Disclaimer

I am not a lawyer.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Badges

Badges w/ shields.io:

![OML](https://img.shields.io/badge/license-OMLv1-blue)
![OML](https://img.shields.io/badge/license-OMLv1.1-blue)
![OML](https://img.shields.io/badge/license-ZOMLv1-blue)
![OML](https://img.shields.io/badge/license-SOMLv1-blue)
![OML](https://img.shields.io/badge/license-NCOMLv1-blue)

## Spread OML

Add a message like this to your model card!

> Share YOUR model under the permissive Open Model License, a NEW approach to AI model licensing. Stop trying to fit software licenses to your AI model. Does "source code" apply to AI models? Don't worry about that - just use the [Open Model License](https://github.com/fakerybakery/OpenModelLicense)!

Markdown:

```markdown
Share YOUR model under the permissive Open Model License, a NEW approach to AI model licensing. Stop trying to fit software licenses to your AI model. Does "source code" apply to AI models? Don't worry about that - just use the [Open Model License](https://github.com/fakerybakery/OpenModelLicense)!
```

### Spread OML Badge

Apply this everywhere! Looks beautiful anywhere and everywhere! Put it on your Hugging Face Model Cards, add it to your GitHub repos, put it on stuff that isn't even remotely related to AI!

![Spread OML](https://img.shields.io/badge/Spread-Open_Model_License-red)

Markdown:

```markdown
[![Spread OML](https://img.shields.io/badge/Spread-Open_Model_License-red)](https://github.com/fakerybakery/OpenModelLicense)
```

## License of the Licenses

Please license your software under these licenses! Spread open source! These licenses are dedicated to the public domain! Put these on your Hugging Face models to spread the license! The license is in the public domain! **However, we do have one request if you modify this license.** Please refer to the LICENSE file for details.
