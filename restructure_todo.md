# To-do list

* Use `pkgutil.extend_path` to extend `__path__` variable
* Introduce interactive shell with `cmd.Cmd` (?! Maybe overkills)
* Unify constants in unit class (`bajes/obs/utils/units` ?!)
* Use `runpy`  in `__main__` to access different modules/commands
* Introduce timer in `logger`
* Fix `checkpoint_and_exit` in `Sampler`
* Replace `kwargs['case']` with `kwargs.get('case', default)`
* `inf`
   * Introduce hierarchical methods and error propagations
   * Introduce Gelman–Rubin convergence diagnostic for MCMC
   * Check (old) JointPrior with new Parameter settings
* `pipe`
   * Check Binning
   * Check PSD weights
   * Test of GR, e.g. PN tests
   * Parametrized EOS
   * ROQ : Emil
   * Include optional band-passing and padding
   * Sampler is not compatible with kn module ?!
* Improve `postproc`
