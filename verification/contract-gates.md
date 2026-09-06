# Contract Gates

For changes affecting interfaces, verify:

- [ ] API request/response contracts remain compatible or breaking changes are explicitly approved.
- [ ] Database schema/migration behavior is compatible and reversible where practical.
- [ ] Frontend/backend assumptions agree.
- [ ] Authentication and authorization expectations remain aligned.
- [ ] External integrations have failure behavior defined.
- [ ] Versioning/deprecation requirements are addressed where applicable.

Never infer compatibility from compilation alone.