# Cwiczenie-pierwsze-
Zły kod
<Input 
  type="email"
  name="email"
  id="email"
  placeholder="Email"
  valid={touched.email && errors.email ? false : null}
  onChange={handleChange}
  onBlur={handleBlur}
  value={values.email} />
{touched.email && errors.email && <FormFeedback>{errors.email}</FormFeedback>}
