apt-docker CHANGELOG
=====================

This file is used to list changes made in each version of the apt-docker
cookbook.

0.4.0
-----
- St. Isidore de Seville (st.isidore.de.seville@gmail.com)
  - Fix apt cookbook attributes to pass value if value is not nil.  The previous
    behavior was not passing back false values because of the condition and then
    subsequently the value for the apt cookbook may have been defaulting to true
    values.

0.3.0
-----
- Sean OMeara (sean@chef.io)
  - fix Chef 13 deprecation warnings

0.2.0
-----
- St. Isidore de Seville (st.isidore.de.seville@gmail.com)
  - increase unit testing coverage

0.1.0
-----
- St. Isidore de Seville (st.isidore.de.seville@gmail.com)
  - initial release of apt-docker
