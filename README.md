# Front-End Web UI Frameworks and Tools: Bootstrap 4 - Assignment I

This documentation is related to the Coursera course
[Front-End Web UI Frameworks and Tools: Bootstrap 4](https://www.coursera.org/learn/bootstrap-4).

This course is part of the Coursera course set
[Full Stack Web Development with Angular](https://www.coursera.org/specializations/full-stack-mobile-app-development).

### lite-server

This project uses Node.js. To start the lite-server for development, execute: `npm start`. This runs the start script
specified
in
`package.json`. The start script starts the lite-server.

The server can then be reached under `http://localhost:3000/aboutus.html` unless specified differently in the
configuration of the lite-server.

> lite-server uses BrowserSync, and allows for configuration overrides via a local `bs-config.json` file in your
> project.

According to the [lite-server documentation](https://www.npmjs.com/package/lite-server), there is a config file for the
lite-server. It is located at `./configs/bs-config.json`.

## Legacy Code
Code for the reservation card at the bottom:
```
<div class="row row-content justify-content-center" id="reserveTable">
        <div class="card col-12 col-md-8 p-0">
            <h3 class="card-header text-white bg-warning">Reserve a Table</h3>
            <div class="card-body card-">
                <form>
                    <dl class="row">
                        <dt class="col-12 col-sm-4 mb-1 mb-sm-3">Number of guests</dt>
                        <dd class="col-12 col-sm-8 px-3 px-sm-0 mb-3">
                            <div class="custom-control custom-radio custom-control-inline">
                                <input class="custom-control-input" id="radio1" name="radio" type="radio">
                                <label class="custom-control-label" for="radio1">1</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                                <input class="custom-control-input" id="radio2" name="radio" type="radio">
                                <label class="custom-control-label" for="radio2">2</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                                <input class="custom-control-input" id="radio3" name="radio" type="radio">
                                <label class="custom-control-label" for="radio3">3</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                                <input class="custom-control-input" id="radio4" name="radio" type="radio">
                                <label class="custom-control-label" for="radio4">4</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                                <input class="custom-control-input" id="radio5" name="radio" type="radio">
                                <label class="custom-control-label" for="radio5">5</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                                <input class="custom-control-input" id="radio6" name="radio" type="radio">
                                <label class="custom-control-label" for="radio6">6</label>
                            </div>
                        </dd>
                        <dt class="col-12 col-sm-4">Time and Date</dt>
                        <dd class="col-12 col-sm-8">
                            <div class="form-group row px-3 px-sm-0 mt-1 mt-sm-0">
                                <input class="form-control col-12 col-sm-5 mb-1 mb-sm-0" id="date" name="date"
                                       placeholder="Date"
                                       type="text">
                                <input class="form-control col-12 col-sm-5 mx-auto" id="time" name="time"
                                       placeholder="Time"
                                       type="text">
                            </div>
                        </dd>
                        <dt class="px-3 px-sm-0 offset-sm-4">
                            <button class="btn btn-primary" type="submit">Reserve</button>
                        </dt>
                    </dl>
                </form>
            </div>
        </div>
    </div>
</div>
```